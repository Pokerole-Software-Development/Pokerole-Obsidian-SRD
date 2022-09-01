# Datatypes

Rank: Str, the ranks (can be a foreign key?)
DexID: Str, pokedex number plus identified for variant forms

In Obsidian, files are equivlent of rows. This works fine for Pokedex. Move lists I need to look into how to make that one file, then flatten the results into rows. IIRC, same keys get stacked into lists. Moves and Ability are also fine as is. Moves effects, abilities, and ability effects will need the same solution for move lists.

Tree (One item at each Key) - Pokedex, Move
Leaf (Multiple items for each Key) - Move list, Move Effects, Abilities, Ability Effects

Leaves need to be a single file for each key to be pulled via Key. Could be a massive file of objects as well, potentially. 

# SQL Diagram

```mermaid
classDiagram
class Pokedex
class Movelist
class Move
class MoveEffects
class EvolutionTree
class Abilities
class AbilityEffects

Pokedex : str Name
Pokedex : int DexNumber
Pokedex : DexID DexID
Pokedex : int Height
Pokedex : int Weight
Pokedex : bool Starter?
Pokedex : str Type1
Pokedex : str Type2
Pokedex : int StrengthBase
Pokedex : int StrengthMax
Pokedex : int DexterityBase
Pokedex : int DexterityMax
Pokedex : int VitalityBase
Pokedex : int VitalityMax
Pokedex : int SpecialBase
Pokedex : int SpecialMax
Pokedex : int InsightBase
Pokedex : int InsightMax
Pokedex : int BaseHp
Pokedex : Rank SuggestedRank
Pokedex : str Ability1
Pokedex : str Ability2
Pokedex : str Ability3

Movelist : DexID DexID
Movelist : Rank Rank
Movelist : str MoveName

Move : str Name
Move : str Type
Move : str DmgType
Move : int Power
Move : str Accuracy
Move : str Damage
Move : str Effect
Move : str Flavor
Move : int EffectsId

MoveEffects : str MoveName
MoveEffects : str Effect

EvolutionTree : DexID Base 
EvolutionTree : DexID Evolved
EvolutionTree : str Notes

Abilities : str Name
Abilities : str Rules
Abilities : str Flavor
Abilities : int AbilityId

AbilityEffects : int AbilityId
AbilityEffects : str Effect

Pokedex --> Movelist : DexID
Pokedex --> EvolutionTree : DexId
Pokedex --> Abilities : Ability 1-3
Abilities --> AbilityEffects: AbilityId
Movelist --> Move : MoveName
Move --> MoveEffects : MoveName


```

# Dataview Templates

DexID must be a string, as must links in lists. 

DexID = four digit pokedex number, indicator of variant
Variants: **G**alar, **A**lolan, **H**isuian, **P**aldean, **M**ega, 

## Move lists

---
dexID: "0001"
moves: 
 - [Starter, "[[Tackle]]"]
 - [Starter, "[[Growl]]"]
---

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM "Pokerole SRD/Movelists"
flatten moves as T
where file.name = this.file.name
```