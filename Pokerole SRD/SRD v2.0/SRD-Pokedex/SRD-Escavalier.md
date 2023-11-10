---
Ability1: Swarm
Ability2: Shell Armor
BookSprite: SRD-escavalier-BookSprite.png
BoxSprite: SRD-escavalier-BoxSprite.png
DexCategory: Cavalry Pokemon
DexDescription: Wearing the shell covering it stole from a Shelmet, it defends itself
  and attacks with two stings. It can fly to move around but its wings are too small
  to carry its weight to high altitudes.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Karrablast]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Overcoat
HomeSprite: SRD-escavalier-HomeSprite.png
Image: escavalier.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Beginner
  - '[[SRD-Twineedle|Twineedle]]'
- - Beginner
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Megahorn|Megahorn]]'
- - Pro
  - '[[SRD-Drill Run|Drill Run]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
Number: 589
ShuffleToken: SRD-escavalier-ShuffleToken.png
Type1: Bug
Type2: Steel
Weight:
  Kilograms: 33.0
  Pounds: 72.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-escavalier-BookSprite.png|wsmall]]
> ![[SRD-escavalier-HomeSprite.png]]
> ![[SRD-escavalier-BoxSprite.png|htiny]]
> ![[SRD-escavalier-ShuffleToken.png|wsmall]]


*Cavalry Pokemon*
*Wearing the shell covering it stole from a Shelmet, it defends itself and attacks with two stings. It can fly to move around but its wings are too small to carry its weight to high altitudes.*

**DexID**:: 0589
**Name**:: Escavalier
**Type**:: Bug / Steel
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Shell Armor|Shell Armor]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'3" / 1.0m
**Weight**: 72.8lbs / 33.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Karrablast]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Escavalier.md"
flatten moves as T
where file.path = this.file.path
```
