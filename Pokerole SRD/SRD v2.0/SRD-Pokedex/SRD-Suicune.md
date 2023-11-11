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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bubble Beam|Bubble Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gust|Gust]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aurora Beam|Aurora Beam]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mist|Mist]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mirror Coat|Mirror Coat]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ice Fang|Ice Fang]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tailwind|Tailwind]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Blizzard|Blizzard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double Team|Double Team]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Substitute|Substitute]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dive|Dive]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ominous Wind|Ominous Wind]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mimic|Mimic]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Curse|Curse]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sheer Cold|Sheer Cold]]'
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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Suicune.md"
flatten moves as T
where file.path = this.file.path
```
