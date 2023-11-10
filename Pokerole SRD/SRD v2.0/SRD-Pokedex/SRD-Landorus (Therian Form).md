---
Ability1: Sand Force
Ability2: ''
BookSprite: SRD-landorus-therian-form-BookSprite.png
BoxSprite: SRD-landorus-therian-form-BoxSprite.png
DexCategory: No Data
DexDescription: Some Pokemon reveal their true forms after recovering power lost to
  them. Great forces of nature can help them recover their strength such as Tornadoes,
  Lightning, and even a Landslide.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Landorus]]'
GenderType: M
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Sheer Force
HomeSprite: SRD-landorus-therian-form-HomeSprite.png
Image: landorus-therian-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Block|Block]]'
- - Master
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Master
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Master
  - '[[SRD-Imprison|Imprison]]'
- - Master
  - '[[SRD-Punishment|Punishment]]'
- - Master
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Master
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Master
  - '[[SRD-Earthquake|Earthquake]]'
- - Master
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Master
  - '[[SRD-Fissure|Fissure]]'
- - Master
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Rototiller|Rototiller]]'
- - Master
  - '[[SRD-Dig|Dig]]'
Number: 645
ShuffleToken: SRD-landorus-therian-form-ShuffleToken.png
Type1: Ground
Type2: Flying
Weight:
  Kilograms: 68.0
  Pounds: 149.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-landorus-therian-form-BookSprite.png|wsmall]]
> ![[SRD-landorus-therian-form-HomeSprite.png]]
> ![[SRD-landorus-therian-form-BoxSprite.png|htiny]]
> ![[SRD-landorus-therian-form-ShuffleToken.png|wsmall]]


*No Data*
*Some Pokemon reveal their true forms after recovering power lost to them. Great forces of nature can help them recover their strength such as Tornadoes, Lightning, and even a Landslide.*

**DexID**:: 0645F1
**Name**:: Landorus (Therian Form)
**Type**:: Ground / Flying
**Abilities**:: [[SRD-Sand Force|Sand Force]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 149.9lbs / 68.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon          | Kind   |
|:----------|:-----------------|:-------|
| From      | [[SRD-Landorus]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Landorus (Therian Form).md"
flatten moves as T
where file.path = this.file.path
```
