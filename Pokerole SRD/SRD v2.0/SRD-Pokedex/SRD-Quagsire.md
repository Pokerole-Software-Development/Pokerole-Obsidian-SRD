---
Ability1: Damp
Ability2: Water Absorb
BookSprite: SRD-quagsire-BookSprite.png
BoxSprite: SRD-quagsire-BoxSprite.png
DexCategory: Water Fish Pokemon
DexDescription: "You\u2019ll find its home at the bottom of the river. It hunts by\
  \ leaving its mouth wide open in water and waiting for its prey to get in. Because\
  \ it doesn\u2019t move a lot, it does not get very hungry."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Wooper]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Unaware
HomeSprite: SRD-quagsire-HomeSprite.png
Image: quagsire.png
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
Number: 195
ShuffleToken: SRD-quagsire-ShuffleToken.png
Type1: Water
Type2: Ground
Weight:
  Kilograms: 75.0
  Pounds: 165.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-quagsire-BookSprite.png|wsmall]]
> ![[SRD-quagsire-HomeSprite.png]]
> ![[SRD-quagsire-BoxSprite.png|htiny]]
> ![[SRD-quagsire-ShuffleToken.png|wsmall]]


*Water Fish Pokemon*
*You’ll find its home at the bottom of the river. It hunts by leaving its mouth wide open in water and waiting for its prey to get in. Because it doesn’t move a lot, it does not get very hungry.*

**DexID**:: 0195
**Name**:: Quagsire
**Type**:: Water / Ground
**Abilities**:: [[SRD-Damp|Damp]] / [[SRD-Water Absorb|Water Absorb]] ([[SRD-Unaware|Unaware]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'6" / 1.4m
**Weight**: 165.3lbs / 75.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Wooper]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Quagsire.md"
flatten moves as T
where file.path = this.file.path
```
