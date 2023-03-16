---
Ability1: Inner Focus
Ability2: Synchronize
BookSprite: SRD-indeedee-BookSprite.png
BoxSprite: SRD-indeedee-BoxSprite.png
DexCategory: Emotion Pokemon
DexDescription: These intelligent Pokemon touch horns with each other to share information
  between them. They love to help and be of service to people because they gather
  power from feelings of gratitude.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Psychic Surge
HomeSprite: SRD-indeedee-HomeSprite.png
Image: indeedee.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Stored Power|Stored Power]]'
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - Beginner
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Follow Me|Follow Me]]'
- - Amateur
  - '[[SRD-After You|After You]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Power Split|Power Split]]'
- - Ace
  - '[[SRD-Guard Split|Guard Split]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Ace
  - '[[SRD-Psychic Terrain|Psychic Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
Number: 876
ShuffleToken: SRD-indeedee-ShuffleToken.png
Type1: Psychic
Type2: Normal
Weight:
  Kilograms: 28.0
  Pounds: 61.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-indeedee-BookSprite.png|wsmall]]
> ![[SRD-indeedee-HomeSprite.png]]
> ![[SRD-indeedee-BoxSprite.png|htiny]]
> ![[SRD-indeedee-ShuffleToken.png|wsmall]]


*Emotion Pokemon*
*These intelligent Pokemon touch horns with each other to share information between them. They love to help and be of service to people because they gather power from feelings of gratitude.*

**DexID**:: 0876
**Name**:: Indeedee
**Type**:: Psychic / Normal
**Abilities**:: [[SRD-Inner Focus|Inner Focus]] / [[SRD-Synchronize|Synchronize]] ([[SRD-Psychic Surge|Psychic Surge]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'0" / 0.9m
**Weight**: 61.7lbs / 28.0kg
**Good Starter**:: No
**Recommended Rank**:: Starter

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Indeedee.md"
flatten moves as T
where file.path = this.file.path
```
