---
Ability1: Prankster
Ability2: ''
BookSprite: SRD-thundurus-therian-form-BookSprite.png
BoxSprite: SRD-thundurus-therian-form-BoxSprite.png
DexCategory: No Data
DexDescription: Some Pokemon reveal their true forms after recovering power lost to
  them. Great forces of nature can help them recover their strength such as Tornadoes,
  Lightning, and even a Landslide.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Thundurus]]'
GenderType: M
Height:
  Feet: 9.8
  Meters: 3.0
HiddenAbility: Defiant
HomeSprite: SRD-thundurus-therian-form-HomeSprite.png
Image: thundurus-therian-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Uproar|Uproar]]'
- - Master
  - '[[SRD-Astonish|Astonish]]'
- - Master
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Master
  - '[[SRD-Swagger|Swagger]]'
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Revenge|Revenge]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[SRD-Heal Block|Heal Block]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Discharge|Discharge]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Charge|Charge]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Thunder|Thunder]]'
- - Master
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Thrash|Thrash]]'
- - Master
  - '[[SRD-Ion Deluge|Ion Deluge]]'
- - Master
  - '[[SRD-Electric Terrain|Electric Terrain]]'
Number: 642
ShuffleToken: SRD-thundurus-therian-form-ShuffleToken.png
Type1: Electric
Type2: Flying
Weight:
  Kilograms: 61.0
  Pounds: 134.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-thundurus-therian-form-BookSprite.png|wsmall]]
> ![[SRD-thundurus-therian-form-HomeSprite.png]]
> ![[SRD-thundurus-therian-form-BoxSprite.png|htiny]]
> ![[SRD-thundurus-therian-form-ShuffleToken.png|wsmall]]


*No Data*
*Some Pokemon reveal their true forms after recovering power lost to them. Great forces of nature can help them recover their strength such as Tornadoes, Lightning, and even a Landslide.*

**DexID**:: 0642F1
**Name**:: Thundurus (Therian Form)
**Type**:: Electric / Flying
**Abilities**:: [[SRD-Prankster|Prankster]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 9'8" / 3.0m
**Weight**: 134.5lbs / 61.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon           | Kind   |
|:----------|:------------------|:-------|
| From      | [[SRD-Thundurus]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Thundurus (Therian Form).md"
flatten moves as T
where file.path = this.file.path
```
