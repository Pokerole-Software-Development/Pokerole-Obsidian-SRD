---
Ability1: Cute Charm
Ability2: Competitive
BookSprite: SRD-jigglypuff-BookSprite.png
BoxSprite: SRD-jigglypuff-BoxSprite.png
DexCategory: Balloon Pokemon
DexDescription: They live in grassy fields near the mountains. To climb they inflate
  their bodies and bounce up. It captivates foes with its huge, round eyes, then lulls
  them to sleep by singing a sweet soothing melody.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Igglybuff]]'
  Stat: Happiness
  Value: 4
- Evolves: To
  Item: Moon Stone
  Kind: Stone
  Pokemon: '[[SRD-Wigglytuff]]'
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Friend Guard
HomeSprite: SRD-jigglypuff-HomeSprite.png
Image: jigglypuff.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sing|Sing]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Play Nice|Play Nice]]'
- - Beginner
  - '[[SRD-Round|Round]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - Amateur
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Ace
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mimic|Mimic]]'
- - Pro
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
Number: 39
ShuffleToken: SRD-jigglypuff-ShuffleToken.png
Type1: Normal
Type2: Fairy
Weight:
  Kilograms: 5.5
  Pounds: 12.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-jigglypuff-BookSprite.png|wsmall]]
> ![[SRD-jigglypuff-HomeSprite.png]]
> ![[SRD-jigglypuff-BoxSprite.png|htiny]]
> ![[SRD-jigglypuff-ShuffleToken.png|wsmall]]


*Balloon Pokemon*
*They live in grassy fields near the mountains. To climb they inflate their bodies and bounce up. It captivates foes with its huge, round eyes, then lulls them to sleep by singing a sweet soothing melody.*

**DexID**:: 0039
**Name**:: Jigglypuff
**Type**:: Normal / Fairy
**Abilities**:: [[SRD-Cute Charm|Cute Charm]] / [[SRD-Competitive|Competitive]] ([[SRD-Friend Guard|Friend Guard]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 12.1lbs / 5.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Stat      | Value   | Item       |
|:----------|:-------------------|:-------|:----------|:--------|:-----------|
| From      | [[SRD-Igglybuff]]  | Stat   | Happiness | 4.0     |            |
| To        | [[SRD-Wigglytuff]] | Stone  |           |         | Moon Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Jigglypuff.md"
flatten moves as T
where file.path = this.file.path
```
