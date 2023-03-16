---
Ability1: Electric Surge
Ability2: ''
BookSprite: SRD-tapu-koko-BookSprite.png
BoxSprite: SRD-tapu-koko-BoxSprite.png
DexCategory: No Data
DexDescription: People on Melemele island talk about a guardian spirit who punishes
  the evil doers with lightning strikes. If it appears in front of you who knows what
  its intentions may be.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Telepathy
HomeSprite: SRD-tapu-koko-HomeSprite.png
Image: tapu-koko.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - Master
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Master
  - '[[SRD-Power Swap|Power Swap]]'
- - Master
  - '[[SRD-Mean Look|Mean Look]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-False Swipe|False Swipe]]'
- - Master
  - '[[SRD-Withdraw|Withdraw]]'
- - Master
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Master
  - '[[SRD-Spark|Spark]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[SRD-Screech|Screech]]'
- - Master
  - '[[SRD-Charge|Charge]]'
- - Master
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Master
  - '[[SRD-Mirror Move|Mirror Move]]'
- - Master
  - '[[SRD-Nature''s Madness|Nature''s Madness]]'
- - Master
  - '[[SRD-Discharge|Discharge]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Master
  - '[[SRD-Defog|Defog]]'
Number: 785
ShuffleToken: SRD-tapu-koko-ShuffleToken.png
Type1: Electric
Type2: Fairy
Weight:
  Kilograms: 20.5
  Pounds: 45.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tapu-koko-BookSprite.png|wsmall]]
> ![[SRD-tapu-koko-HomeSprite.png]]
> ![[SRD-tapu-koko-BoxSprite.png|htiny]]
> ![[SRD-tapu-koko-ShuffleToken.png|wsmall]]


*No Data*
*People on Melemele island talk about a guardian spirit who punishes the evil doers with lightning strikes. If it appears in front of you who knows what its intentions may be.*

**DexID**:: 0785
**Name**:: Tapu Koko
**Type**:: Electric / Fairy
**Abilities**:: [[SRD-Electric Surge|Electric Surge]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 45.2lbs / 20.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Tapu Koko.md"
flatten moves as T
where file.path = this.file.path
```
