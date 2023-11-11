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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Uproar|Uproar]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Astonish|Astonish]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Shock|Thunder Shock]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swagger|Swagger]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Revenge|Revenge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heal Block|Heal Block]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Discharge|Discharge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder|Thunder]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thrash|Thrash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ion Deluge|Ion Deluge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Electric Terrain|Electric Terrain]]'
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
