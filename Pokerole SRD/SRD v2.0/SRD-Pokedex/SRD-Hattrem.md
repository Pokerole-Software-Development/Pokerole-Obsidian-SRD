---
Ability1: Healer
Ability2: Anticipation
BookSprite: SRD-hattrem-BookSprite.png
BoxSprite: SRD-hattrem-BoxSprite.png
DexCategory: Serene Pokemon
DexDescription: It may seem friendly but it is actually quite the loner. No matter
  who you are, if you bring strong emotions near it, it will silence you violently
  by hitting you with its braids. It dislikes crowded places.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Hatenna]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Hatterene]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Magic Bounce
HomeSprite: SRD-hattrem-HomeSprite.png
Image: hattrem.png
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
- - Amateur
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Amateur
  - '[[SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Nuzzle|Nuzzle]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Quash|Quash]]'
Number: 857
ShuffleToken: SRD-hattrem-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 4.8
  Pounds: 10.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hattrem-BookSprite.png|wsmall]]
> ![[SRD-hattrem-HomeSprite.png]]
> ![[SRD-hattrem-BoxSprite.png|htiny]]
> ![[SRD-hattrem-ShuffleToken.png|wsmall]]


*Serene Pokemon*
*It may seem friendly but it is actually quite the loner. No matter who you are, if you bring strong emotions near it, it will silence you violently by hitting you with its braids. It dislikes crowded places.*

**DexID**:: 0857
**Name**:: Hattrem
**Type**:: Psychic
**Abilities**:: [[SRD-Healer|Healer]] / [[SRD-Anticipation|Anticipation]] ([[SRD-Magic Bounce|Magic Bounce]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 10.6lbs / 4.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Hatenna]]   | Level  | Medium  |
| To        | [[SRD-Hatterene]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Hattrem.md"
flatten moves as T
where file.path = this.file.path
```
