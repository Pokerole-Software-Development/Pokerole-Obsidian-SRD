---
Ability1: Healer
Ability2: Anticipation
BookSprite: SRD-hatenna-BookSprite.png
BoxSprite: SRD-hatenna-BoxSprite.png
DexCategory: Calm Pokemon
DexDescription: "Though the protrusion on its head it senses other creatures\u2019\
  \ emotions. If you don\u2019t have a calm disposition, it will never warm up to\
  \ you. They get overwhelmed in places with many people, preferring to hide alone."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Hattrem]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Magic Bounce
HomeSprite: SRD-hatenna-HomeSprite.png
Image: hatenna.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Life Dew|Life Dew]]'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Amateur
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Nuzzle|Nuzzle]]'
- - Pro
  - '[[SRD-After You|After You]]'
- - Pro
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
Number: 856
ShuffleToken: SRD-hatenna-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 3.4
  Pounds: 7.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hatenna-BookSprite.png|wsmall]]
> ![[SRD-hatenna-HomeSprite.png]]
> ![[SRD-hatenna-BoxSprite.png|htiny]]
> ![[SRD-hatenna-ShuffleToken.png|wsmall]]


*Calm Pokemon*
*Though the protrusion on its head it senses other creatures’ emotions. If you don’t have a calm disposition, it will never warm up to you. They get overwhelmed in places with many people, preferring to hide alone.*

**DexID**:: 0856
**Name**:: Hatenna
**Type**:: Psychic
**Abilities**:: [[SRD-Healer|Healer]] / [[SRD-Anticipation|Anticipation]] ([[SRD-Magic Bounce|Magic Bounce]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 7.5lbs / 3.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Hattrem]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Hatenna.md"
flatten moves as T
where file.path = this.file.path
```
