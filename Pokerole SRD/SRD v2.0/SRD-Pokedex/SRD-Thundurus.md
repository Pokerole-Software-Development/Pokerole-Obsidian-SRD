---
Ability1: Prankster
Ability2: ''
BookSprite: SRD-thundurus-BookSprite.png
BoxSprite: SRD-thundurus-BoxSprite.png
DexCategory: No Data
DexDescription: "There are constant forest fires all through the Unova region. These\
  \ fires are always the result of a giant thunder storm. Forest rangers tell about\
  \ a blue demon\u2019s shadow that was inside the storm clouds."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Thundurus (Therian Form)]]'
GenderType: M
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Defiant
HomeSprite: SRD-thundurus-HomeSprite.png
Image: thundurus.png
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
ShuffleToken: SRD-thundurus-ShuffleToken.png
Type1: Electric
Type2: Flying
Weight:
  Kilograms: 61.0
  Pounds: 134.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-thundurus-BookSprite.png|wsmall]]
> ![[SRD-thundurus-HomeSprite.png]]
> ![[SRD-thundurus-BoxSprite.png|htiny]]
> ![[SRD-thundurus-ShuffleToken.png|wsmall]]


*No Data*
*There are constant forest fires all through the Unova region. These fires are always the result of a giant thunder storm. Forest rangers tell about a blue demon’s shadow that was inside the storm clouds.*

**DexID**:: 0642
**Name**:: Thundurus
**Type**:: Electric / Flying
**Abilities**:: [[SRD-Prankster|Prankster]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 134.5lbs / 61.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                          | Kind   |
|:----------|:---------------------------------|:-------|
| To        | [[SRD-Thundurus (Therian Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Thundurus.md"
flatten moves as T
where file.path = this.file.path
```
