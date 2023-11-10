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
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Ingrain|Ingrain]]'
- - Master
  - '[[SRD-Absorb|Absorb]]'
- - Master
  - '[[SRD-Harden|Harden]]'
- - Master
  - '[[SRD-Tackle|Tackle]]'
- - Master
  - '[[SRD-Smack Down|Smack Down]]'
- - Master
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Master
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Master
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Master
  - '[[SRD-Iron Head|Iron Head]]'
- - Master
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Master
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Master
  - '[[SRD-Autotomize|Autotomize]]'
- - Master
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Master
  - '[[SRD-Skull Bash|Skull Bash]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Master
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Master
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Master
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Master
  - '[[SRD-Fly|Fly]]'
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
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Celesteela.md"
flatten moves as T
where file.path = this.file.path
```
