---
Ability1: Serene Grace
Ability2: ''
BookSprite: SRD-jirachi-BookSprite.png
BoxSprite: SRD-jirachi-BoxSprite.png
DexCategory: No Data
DexDescription: "It is said that every 1000 years, a shooting star appears in the\
  \ sky for 7 days, granting wishes to those of pure heart. Another common saying\
  \ is: \u201CBe careful what you wish for.\u201D"
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: ''
HomeSprite: SRD-jirachi-HomeSprite.png
Image: jirachi.png
Legendary: 'Yes'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wish|Wish]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Doom Desire|Doom Desire]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Meteor Mash|Meteor Mash]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swift|Swift]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Refresh|Refresh]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lucky Chant|Lucky Chant]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rest|Rest]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gravity|Gravity]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Healing Wish|Healing Wish]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Future Sight|Future Sight]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Cosmic Power|Cosmic Power]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Last Resort|Last Resort]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confide|Confide]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trick|Trick]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trick Room|Trick Room]]'
Number: 385
ShuffleToken: SRD-jirachi-ShuffleToken.png
Type1: Steel
Type2: Psychic
Weight:
  Kilograms: 1.1
  Pounds: 2.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-jirachi-BookSprite.png|wsmall]]
> ![[SRD-jirachi-HomeSprite.png]]
> ![[SRD-jirachi-BoxSprite.png|htiny]]
> ![[SRD-jirachi-ShuffleToken.png|wsmall]]


*No Data*
*It is said that every 1000 years, a shooting star appears in the sky for 7 days, granting wishes to those of pure heart. Another common saying is: “Be careful what you wish for.”*

**DexID**:: 0385
**Name**:: Jirachi
**Type**:: Steel / Psychic
**Abilities**:: [[SRD-Serene Grace|Serene Grace]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 1'0" / 0.3m
**Weight**: 2.4lbs / 1.1kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Jirachi.md"
flatten moves as T
where file.path = this.file.path
```
