---
Ability1: Natural Cure
Ability2: ''
BookSprite: SRD-celebi-BookSprite.png
BoxSprite: SRD-celebi-BoxSprite.png
DexCategory: No Data
DexDescription: Guardian of the Forest. Celebi is said to be able to travel through
  time, amending mistakes from people who hurt the land, and crafting a bright future
  for those who live nearby.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: ''
HomeSprite: SRD-celebi-HomeSprite.png
Image: celebi.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Heal Block|Heal Block]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Master
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Master
  - '[[SRD-Perish Song|Perish Song]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Trick Room|Trick Room]]'
- - Master
  - '[[SRD-Nature Power|Nature Power]]'
- - Master
  - '[[SRD-Worry Seed|Worry Seed]]'
Number: 251
ShuffleToken: SRD-celebi-ShuffleToken.png
Type1: Grass
Type2: Psychic
Weight:
  Kilograms: 5.0
  Pounds: 11.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-celebi-BookSprite.png|wsmall]]
> ![[SRD-celebi-HomeSprite.png]]
> ![[SRD-celebi-BoxSprite.png|htiny]]
> ![[SRD-celebi-ShuffleToken.png|wsmall]]


*No Data*
*Guardian of the Forest. Celebi is said to be able to travel through time, amending mistakes from people who hurt the land, and crafting a bright future for those who live nearby.*

**DexID**:: 0251
**Name**:: Celebi
**Type**:: Grass / Psychic
**Abilities**:: [[SRD-Natural Cure|Natural Cure]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 2'0" / 0.6m
**Weight**: 11.0lbs / 5.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Celebi.md"
flatten moves as T
where file.path = this.file.path
```
