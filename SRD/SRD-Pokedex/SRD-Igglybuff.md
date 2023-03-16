---
Ability1: Cute Charm
Ability2: Competitive
BookSprite: SRD-igglybuff-BookSprite.png
BoxSprite: SRD-igglybuff-BoxSprite.png
DexCategory: Balloon Pokemon
DexDescription: "It has a very light body that makes it float and bounce. If you are\
  \ not careful it can bounce away without control. After being bottle fed it will\
  \ not bounce but wiggle around. It gets cranky if it doesn\u2019t take a nap."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Jigglypuff]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Friend Guard
HomeSprite: SRD-igglybuff-HomeSprite.png
Image: igglybuff.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sing|Sing]]'
- - Starter
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Perish Song|Perish Song]]'
Number: 174
ShuffleToken: SRD-igglybuff-ShuffleToken.png
Type1: Normal
Type2: Fairy
Weight:
  Kilograms: 1.0
  Pounds: 2.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-igglybuff-BookSprite.png|wsmall]]
> ![[SRD-igglybuff-HomeSprite.png]]
> ![[SRD-igglybuff-BoxSprite.png|htiny]]
> ![[SRD-igglybuff-ShuffleToken.png|wsmall]]


*Balloon Pokemon*
*It has a very light body that makes it float and bounce. If you are not careful it can bounce away without control. After being bottle fed it will not bounce but wiggle around. It gets cranky if it doesn’t take a nap.*

**DexID**:: 0174
**Name**:: Igglybuff
**Type**:: Normal / Fairy
**Abilities**:: [[SRD-Cute Charm|Cute Charm]] / [[SRD-Competitive|Competitive]] ([[SRD-Friend Guard|Friend Guard]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::2)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 2.2lbs / 1.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon            | Kind   | Stat      |   Value |
|:----------|:-------------------|:-------|:----------|--------:|
| To        | [[SRD-Jigglypuff]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Igglybuff.md"
flatten moves as T
where file.path = this.file.path
```
