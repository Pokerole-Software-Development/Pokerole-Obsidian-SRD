---
Ability1: Beast Boost
Ability2: ''
BookSprite: SRD-celesteela-BookSprite.png
BoxSprite: SRD-celesteela-BoxSprite.png
DexCategory: 'Aether Foundation Log #019'
DexDescription: Finally some progress from the excavation site. What we thought was
  a 200 year-old relic turned out to be a creature capable of blasting itself into
  the air, we managed to restrain it, more research is due.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 30.2
  Meters: 9.2
HiddenAbility: ''
HomeSprite: SRD-celesteela-HomeSprite.png
Image: celesteela.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Air Slash|Air Slash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ingrain|Ingrain]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Absorb|Absorb]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Harden|Harden]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Smack Down|Smack Down]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mega Drain|Mega Drain]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leech Seed|Leech Seed]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Sound|Metal Sound]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Head|Iron Head]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Drain|Giga Drain]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flash Cannon|Flash Cannon]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Autotomize|Autotomize]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Seed Bomb|Seed Bomb]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Skull Bash|Skull Bash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heavy Slam|Heavy Slam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flame Charge|Flame Charge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magnet Rise|Magnet Rise]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fly|Fly]]'
Number: 797
ShuffleToken: SRD-celesteela-ShuffleToken.png
Type1: Steel
Type2: Flying
Weight:
  Kilograms: 999.9
  Pounds: 2204.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-celesteela-BookSprite.png|wsmall]]
> ![[SRD-celesteela-HomeSprite.png]]
> ![[SRD-celesteela-BoxSprite.png|htiny]]
> ![[SRD-celesteela-ShuffleToken.png|wsmall]]


*Aether Foundation Log #019*
*Finally some progress from the excavation site. What we thought was a 200 year-old relic turned out to be a creature capable of blasting itself into the air, we managed to restrain it, more research is due.*

**DexID**:: 0797
**Name**:: Celesteela
**Type**:: Steel / Flying
**Abilities**:: [[SRD-Beast Boost|Beast Boost]]
**Base HP**:: 9

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 30'2" / 9.2m
**Weight**: 2204.4lbs / 999.9kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Celesteela.md"
flatten moves as T
where file.path = this.file.path
```
