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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Electric Terrain|Electric Terrain]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Brave Bird|Brave Bird]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Power Swap|Power Swap]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mean Look|Mean Look]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-False Swipe|False Swipe]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Withdraw|Withdraw]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Shock|Thunder Shock]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spark|Spark]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Screech|Screech]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wild Charge|Wild Charge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mirror Move|Mirror Move]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nature''s Madness|Nature''s Madness]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Discharge|Discharge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Electro Ball|Electro Ball]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Telekinesis|Telekinesis]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Defog|Defog]]'
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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tapu Koko.md"
flatten moves as T
where file.path = this.file.path
```
