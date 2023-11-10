---
Ability1: Swift Swim
Ability2: ''
BookSprite: SRD-arrokuda-BookSprite.png
BoxSprite: SRD-arrokuda-BoxSprite.png
DexCategory: Rush Pokemon
DexDescription: They propel themselves, swimming at high speeds to hunt their prey.
  After they have eaten their swim becomes sluggish and they are at risk of being
  eaten themselves. They are proud of their pointed jaw.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Barraskewda]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Propeller Tail
HomeSprite: SRD-arrokuda-HomeSprite.png
Image: arrokuda.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - Amateur
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Slash|Slash]]'
- - Pro
  - '[[SRD-Drill Run|Drill Run]]'
- - Pro
  - '[[SRD-Ice Fang|Ice Fang]]'
Number: 846
ShuffleToken: SRD-arrokuda-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 1.0
  Pounds: 2.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-arrokuda-BookSprite.png|wsmall]]
> ![[SRD-arrokuda-HomeSprite.png]]
> ![[SRD-arrokuda-BoxSprite.png|htiny]]
> ![[SRD-arrokuda-ShuffleToken.png|wsmall]]


*Rush Pokemon*
*They propel themselves, swimming at high speeds to hunt their prey. After they have eaten their swim becomes sluggish and they are at risk of being eaten themselves. They are proud of their pointed jaw.*

**DexID**:: 0846
**Name**:: Arrokuda
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] ([[SRD-Propeller Tail|Propeller Tail]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 2.2lbs / 1.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon             | Kind   | Speed   |
|:----------|:--------------------|:-------|:--------|
| To        | [[SRD-Barraskewda]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Arrokuda.md"
flatten moves as T
where file.path = this.file.path
```
