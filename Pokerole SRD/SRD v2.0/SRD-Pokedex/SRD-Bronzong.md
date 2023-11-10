---
Ability1: Levitate
Ability2: Heatproof
BookSprite: SRD-bronzong-BookSprite.png
BoxSprite: SRD-bronzong-BoxSprite.png
DexCategory: Bronze Bell Pokemon
DexDescription: Ancient people revered Bronzong for bringing the rain and sun at will.
  One became a news sensation recently when it was dug up at a construction site after
  a 2000-year sleep.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Bronzor]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Heavy Metal
HomeSprite: SRD-bronzong-HomeSprite.png
Image: bronzong.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Starter
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Imprison|Imprison]]'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Future Sight|Future Sight]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Block|Block]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Ace
  - '[[SRD-Payback|Payback]]'
- - Ace
  - '[[SRD-Heal Block|Heal Block]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
- - Pro
  - '[[SRD-Skill Swap|Skill Swap]]'
Number: 437
ShuffleToken: SRD-bronzong-ShuffleToken.png
Type1: Steel
Type2: Psychic
Weight:
  Kilograms: 187.0
  Pounds: 412.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bronzong-BookSprite.png|wsmall]]
> ![[SRD-bronzong-HomeSprite.png]]
> ![[SRD-bronzong-BoxSprite.png|htiny]]
> ![[SRD-bronzong-ShuffleToken.png|wsmall]]


*Bronze Bell Pokemon*
*Ancient people revered Bronzong for bringing the rain and sun at will. One became a news sensation recently when it was dug up at a construction site after a 2000-year sleep.*

**DexID**:: 0437
**Name**:: Bronzong
**Type**:: Steel / Psychic
**Abilities**:: [[SRD-Levitate|Levitate]] / [[SRD-Heatproof|Heatproof]] ([[SRD-Heavy Metal|Heavy Metal]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'3" / 1.3m
**Weight**: 412.3lbs / 187.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Bronzor]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Bronzong.md"
flatten moves as T
where file.path = this.file.path
```
