---
Ability1: Soul Heart
Ability2: ''
BookSprite: SRD-magearna-BookSprite.png
BoxSprite: SRD-magearna-BoxSprite.png
DexCategory: No Data
DexDescription: 500 years ago a famous scientist left a manuscript with details on
  how to create a mechanic Pokemon. His investigation led to the creation of the modern
  Pokeball.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: ''
HomeSprite: SRD-magearna-HomeSprite.png
Image: magearna.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Crafty Shield|Crafty Shield]]'
- - Master
  - '[[SRD-Gear Up|Gear Up]]'
- - Master
  - '[[SRD-Shift Gear|Shift Gear]]'
- - Master
  - '[[SRD-Iron Head|Iron Head]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Sonic Boom|Sonic Boom]]'
- - Master
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Master
  - '[[SRD-Psybeam|Psybeam]]'
- - Master
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Master
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Master
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Master
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Master
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Master
  - '[[SRD-Fleur Cannon|Fleur Cannon]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Pain Split|Pain Split]]'
- - Master
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Master
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Master
  - '[[SRD-Heart Swap|Heart Swap]]'
- - Master
  - '[[SRD-Trump Card|Trump Card]]'
- - Master
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Master
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Master
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
Number: 801
ShuffleToken: SRD-magearna-ShuffleToken.png
Type1: Steel
Type2: Fairy
Weight:
  Kilograms: 80.5
  Pounds: 177.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-magearna-BookSprite.png|wsmall]]
> ![[SRD-magearna-HomeSprite.png]]
> ![[SRD-magearna-BoxSprite.png|htiny]]
> ![[SRD-magearna-ShuffleToken.png|wsmall]]


*No Data*
*500 years ago a famous scientist left a manuscript with details on how to create a mechanic Pokemon. His investigation led to the creation of the modern Pokeball.*

**DexID**:: 0801
**Name**:: Magearna
**Type**:: Steel / Fairy
**Abilities**:: [[SRD-Soul Heart|Soul Heart]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 3'3" / 1.0m
**Weight**: 177.5lbs / 80.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Magearna.md"
flatten moves as T
where file.path = this.file.path
```
