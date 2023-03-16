---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-suicune-BookSprite.png
BoxSprite: SRD-suicune-BoxSprite.png
DexCategory: No Data
DexDescription: Johto Legends tell about a Pokemon that carries the north winds, sailing
  above the clouds as the aurora, purifying water fountains, pools and rivers.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Inner Focus
HomeSprite: SRD-suicune-HomeSprite.png
Image: suicune.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Gust|Gust]]'
- - Master
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Master
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Blizzard|Blizzard]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Substitute|Substitute]]'
- - Master
  - '[[SRD-Dive|Dive]]'
- - Master
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Master
  - '[[SRD-Mimic|Mimic]]'
- - Master
  - '[[SRD-Curse|Curse]]'
- - Master
  - '[[SRD-Sheer Cold|Sheer Cold]]'
Number: 245
ShuffleToken: SRD-suicune-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 187.0
  Pounds: 412.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-suicune-BookSprite.png|wsmall]]
> ![[SRD-suicune-HomeSprite.png]]
> ![[SRD-suicune-BoxSprite.png|htiny]]
> ![[SRD-suicune-ShuffleToken.png|wsmall]]


*No Data*
*Johto Legends tell about a Pokemon that carries the north winds, sailing above the clouds as the aurora, purifying water fountains, pools and rivers.*

**DexID**:: 0245
**Name**:: Suicune
**Type**:: Water
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Inner Focus|Inner Focus]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 6'6" / 2.0m
**Weight**: 412.3lbs / 187.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Suicune.md"
flatten moves as T
where file.path = this.file.path
```
