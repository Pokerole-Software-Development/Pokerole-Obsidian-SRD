---
Ability1: Damp
Ability2: Water Absorb
BookSprite: SRD-wooper-BookSprite.png
BoxSprite: SRD-wooper-BoxSprite.png
DexCategory: Water Fish Pokemon
DexDescription: Inhabits cold water sources and only comes out during the evening
  when the land has cooled, to find something to eat. Under this ideal environment
  it has rarely been seen at its evolved stage.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Quagsire]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Unaware
HomeSprite: SRD-wooper-HomeSprite.png
Image: wooper.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Beginner
  - '[[SRD-Mud Shot|Mud Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Muddy Water|Muddy Water]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Haze|Haze]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Curse|Curse]]'
- - Pro
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
Number: 194
ShuffleToken: SRD-wooper-ShuffleToken.png
Type1: Water
Type2: Ground
Weight:
  Kilograms: 8.5
  Pounds: 18.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wooper-BookSprite.png|wsmall]]
> ![[SRD-wooper-HomeSprite.png]]
> ![[SRD-wooper-BoxSprite.png|htiny]]
> ![[SRD-wooper-ShuffleToken.png|wsmall]]


*Water Fish Pokemon*
*Inhabits cold water sources and only comes out during the evening when the land has cooled, to find something to eat. Under this ideal environment it has rarely been seen at its evolved stage.*

**DexID**:: 0194
**Name**:: Wooper
**Type**:: Water / Ground
**Abilities**:: [[SRD-Damp|Damp]] / [[SRD-Water Absorb|Water Absorb]] ([[SRD-Unaware|Unaware]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 18.7lbs / 8.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Quagsire]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Wooper.md"
flatten moves as T
where file.path = this.file.path
```
