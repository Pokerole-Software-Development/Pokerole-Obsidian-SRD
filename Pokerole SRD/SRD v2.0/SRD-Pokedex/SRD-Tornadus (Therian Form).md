---
Ability1: Regenerator
Ability2: ''
BookSprite: SRD-tornadus-therian-form-BookSprite.png
BoxSprite: SRD-tornadus-therian-form-BoxSprite.png
DexCategory: No Data
DexDescription: Some Pokemon reveal their true forms after recovering power lost to
  them. Great forces of nature can help them recover their strength such as Tornadoes,
  Lightning, and even a Landslide.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Tornadus]]'
GenderType: M
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-tornadus-therian-form-HomeSprite.png
Image: tornadus-therian-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Uproar|Uproar]]'
- - Master
  - '[[SRD-Astonish|Astonish]]'
- - Master
  - '[[SRD-Gust|Gust]]'
- - Master
  - '[[SRD-Swagger|Swagger]]'
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Revenge|Revenge]]'
- - Master
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Thrash|Thrash]]'
- - Master
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Master
  - '[[SRD-Defog|Defog]]'
Number: 641
ShuffleToken: SRD-tornadus-therian-form-ShuffleToken.png
Type1: Flying
Type2: ''
Weight:
  Kilograms: 63.0
  Pounds: 138.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tornadus-therian-form-BookSprite.png|wsmall]]
> ![[SRD-tornadus-therian-form-HomeSprite.png]]
> ![[SRD-tornadus-therian-form-BoxSprite.png|htiny]]
> ![[SRD-tornadus-therian-form-ShuffleToken.png|wsmall]]


*No Data*
*Some Pokemon reveal their true forms after recovering power lost to them. Great forces of nature can help them recover their strength such as Tornadoes, Lightning, and even a Landslide.*

**DexID**:: 0641F1
**Name**:: Tornadus (Therian Form)
**Type**:: Flying
**Abilities**:: [[SRD-Regenerator|Regenerator]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 138.9lbs / 63.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon          | Kind   |
|:----------|:-----------------|:-------|
| From      | [[SRD-Tornadus]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tornadus (Therian Form).md"
flatten moves as T
where file.path = this.file.path
```
