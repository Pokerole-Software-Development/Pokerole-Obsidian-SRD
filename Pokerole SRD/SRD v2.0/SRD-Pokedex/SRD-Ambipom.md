---
Ability1: Technician
Ability2: Pickup
BookSprite: SRD-ambipom-BookSprite.png
BoxSprite: SRD-ambipom-BoxSprite.png
DexCategory: Long Tail Pokemon
DexDescription: They live in large colonies on the tallest trees, linking their tails
  to show friendship among herd mates. It loves fresh fruit. Ambipom uses its two
  tails better than its own arms to swing around.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Aipom]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Skill Link
HomeSprite: SRD-ambipom-HomeSprite.png
Image: ambipom.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Beginner
  - '[[SRD-Baton Pass|Baton Pass]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Tickle|Tickle]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
Number: 424
ShuffleToken: SRD-ambipom-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 20.3
  Pounds: 44.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ambipom-BookSprite.png|wsmall]]
> ![[SRD-ambipom-HomeSprite.png]]
> ![[SRD-ambipom-BoxSprite.png|htiny]]
> ![[SRD-ambipom-ShuffleToken.png|wsmall]]


*Long Tail Pokemon*
*They live in large colonies on the tallest trees, linking their tails to show friendship among herd mates. It loves fresh fruit. Ambipom uses its two tails better than its own arms to swing around.*

**DexID**:: 0424
**Name**:: Ambipom
**Type**:: Normal
**Abilities**:: [[SRD-Technician|Technician]] / [[SRD-Pickup|Pickup]] ([[SRD-Skill Link|Skill Link]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 44.8lbs / 20.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| From      | [[SRD-Aipom]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ambipom.md"
flatten moves as T
where file.path = this.file.path
```
