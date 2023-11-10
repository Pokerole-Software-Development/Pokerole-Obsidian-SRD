---
Ability1: Tangled Feet
Ability2: Screen Cleaner
BookSprite: SRD-mr-rime-BookSprite.png
BoxSprite: SRD-mr-rime-BoxSprite.png
DexCategory: Comedian Pokemon
DexDescription: "It\u2019s highly skilled at tap-dancing. It waves its cane of ice\
  \ in time, its amusing movements make it very popular and they love to entertain\
  \ children. It releases all of its psychic power from the pattern on its belly."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Mr. Mime (Galarian Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Ice Body
HomeSprite: SRD-mr-rime-HomeSprite.png
Image: mr-rime.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Slack Off|Slack Off]]'
- - Starter
  - '[[SRD-After You|After You]]'
- - Starter
  - '[[SRD-Block|Block]]'
- - Starter
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Beginner
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Ally Switch|Ally Switch]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Role Play|Role Play]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Recycle|Recycle]]'
- - Amateur
  - '[[SRD-Mimic|Mimic]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Ace
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Ace
  - '[[SRD-Teeter Dance|Teeter Dance]]'
Number: 866
ShuffleToken: SRD-mr-rime-ShuffleToken.png
Type1: Ice
Type2: Psychic
Weight:
  Kilograms: 58.2
  Pounds: 128.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mr-rime-BookSprite.png|wsmall]]
> ![[SRD-mr-rime-HomeSprite.png]]
> ![[SRD-mr-rime-BoxSprite.png|htiny]]
> ![[SRD-mr-rime-ShuffleToken.png|wsmall]]


*Comedian Pokemon*
*It’s highly skilled at tap-dancing. It waves its cane of ice in time, its amusing movements make it very popular and they love to entertain children. It releases all of its psychic power from the pattern on its belly.*

**DexID**:: 0866
**Name**:: Mr. Rime
**Type**:: Ice / Psychic
**Abilities**:: [[SRD-Tangled Feet|Tangled Feet]] / [[SRD-Screen Cleaner|Screen Cleaner]] ([[SRD-Ice Body|Ice Body]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 128.3lbs / 58.2kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                          | Kind   | Speed   |
|:----------|:---------------------------------|:-------|:--------|
| From      | [[SRD-Mr. Mime (Galarian Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mr. Rime.md"
flatten moves as T
where file.path = this.file.path
```
