---
Ability1: Healer
Ability2: Anticipation
BookSprite: SRD-hatterene-BookSprite.png
BoxSprite: SRD-hatterene-BoxSprite.png
DexCategory: Silent Pokemon
DexDescription: "If you\u2019re too loud around it, you risk being torn apart by the\
  \ claws on its tentacle. This Pokemon is also known as the Forest Witch. It is very\
  \ sensitive to the emotions of others if it senses doubt, fear or anger it will\
  \ attack you."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Hattrem]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: Magic Bounce
HomeSprite: SRD-hatterene-HomeSprite.png
Image: hatterene.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Play Nice|Play Nice]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Life Dew|Life Dew]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Disarming Voice|Disarming Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heal Pulse|Heal Pulse]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Calm Mind|Calm Mind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Brutal Swing|Brutal Swing]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psycho Cut|Psycho Cut]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Healing Wish|Healing Wish]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magic Powder|Magic Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dark Pulse|Dark Pulse]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mystical Fire|Mystical Fire]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Light Screen|Light Screen]]'
Number: 858
ShuffleToken: SRD-hatterene-ShuffleToken.png
Type1: Psychic
Type2: Fairy
Weight:
  Kilograms: 5.1
  Pounds: 11.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hatterene-BookSprite.png|wsmall]]
> ![[SRD-hatterene-HomeSprite.png]]
> ![[SRD-hatterene-BoxSprite.png|htiny]]
> ![[SRD-hatterene-ShuffleToken.png|wsmall]]


*Silent Pokemon*
*If you’re too loud around it, you risk being torn apart by the claws on its tentacle. This Pokemon is also known as the Forest Witch. It is very sensitive to the emotions of others if it senses doubt, fear or anger it will attack you.*

**DexID**:: 0858
**Name**:: Hatterene
**Type**:: Psychic / Fairy
**Abilities**:: [[SRD-Healer|Healer]] / [[SRD-Anticipation|Anticipation]] ([[SRD-Magic Bounce|Magic Bounce]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 6'9" / 2.1m
**Weight**: 11.2lbs / 5.1kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Hattrem]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Hatterene.md"
flatten moves as T
where file.path = this.file.path
```
