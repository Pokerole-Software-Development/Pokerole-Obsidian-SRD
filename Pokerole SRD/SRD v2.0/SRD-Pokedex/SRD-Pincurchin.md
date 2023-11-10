---
Ability1: Lightning Rod
Ability2: ''
BookSprite: SRD-pincurchin-BookSprite.png
BoxSprite: SRD-pincurchin-BoxSprite.png
DexCategory: Sea Urchin Pokemon
DexDescription: This quiet pokemon feeds on sea weed, using its teeth to scrape it
  off rocks. It stores electricity in each of its spines. Even if one gets broken
  off, it will continue to emit electricity for a few more hours.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Electric Surge
HomeSprite: SRD-pincurchin-HomeSprite.png
Image: pincurchin.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Ace
  - '[[SRD-Zing Zap|Zing Zap]]'
- - Ace
  - '[[SRD-Acupressure|Acupressure]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Pro
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
Number: 871
ShuffleToken: SRD-pincurchin-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 1.0
  Pounds: 2.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pincurchin-BookSprite.png|wsmall]]
> ![[SRD-pincurchin-HomeSprite.png]]
> ![[SRD-pincurchin-BoxSprite.png|htiny]]
> ![[SRD-pincurchin-ShuffleToken.png|wsmall]]


*Sea Urchin Pokemon*
*This quiet pokemon feeds on sea weed, using its teeth to scrape it off rocks. It stores electricity in each of its spines. Even if one gets broken off, it will continue to emit electricity for a few more hours.*

**DexID**:: 0871
**Name**:: Pincurchin
**Type**:: Electric
**Abilities**:: [[SRD-Lightning Rod|Lightning Rod]] ([[SRD-Electric Surge|Electric Surge]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'0" / 0.3m
**Weight**: 2.2lbs / 1.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pincurchin.md"
flatten moves as T
where file.path = this.file.path
```
