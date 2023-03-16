---
Ability1: Run Away
Ability2: Klutz
BookSprite: SRD-buneary-BookSprite.png
BoxSprite: SRD-buneary-BoxSprite.png
DexCategory: Rabbit Pokemon
DexDescription: Lives in forest, grasslands and even snowy mountains. It forms burrows
  and uses its soft fur to make nests and keep warm. You can see how it feels for
  the position of its ears. They are easily scared by humans.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Lopunny]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Limber
HomeSprite: SRD-buneary-HomeSprite.png
Image: buneary.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Starter
  - '[[SRD-Splash|Splash]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Endure|Endure]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Frustration|Frustration]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Jump Kick|Jump Kick]]'
- - Amateur
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Dizzy Punch|Dizzy Punch]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-After You|After You]]'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
Number: 427
ShuffleToken: SRD-buneary-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 5.5
  Pounds: 12.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-buneary-BookSprite.png|wsmall]]
> ![[SRD-buneary-HomeSprite.png]]
> ![[SRD-buneary-BoxSprite.png|htiny]]
> ![[SRD-buneary-ShuffleToken.png|wsmall]]


*Rabbit Pokemon*
*Lives in forest, grasslands and even snowy mountains. It forms burrows and uses its soft fur to make nests and keep warm. You can see how it feels for the position of its ears. They are easily scared by humans.*

**DexID**:: 0427
**Name**:: Buneary
**Type**:: Normal
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Klutz|Klutz]] ([[SRD-Limber|Limber]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 12.1lbs / 5.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Stat      |   Value |
|:----------|:----------------|:-------|:----------|--------:|
| To        | [[SRD-Lopunny]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Buneary.md"
flatten moves as T
where file.path = this.file.path
```
