---
Ability1: Cute Charm
Ability2: Klutz
BookSprite: SRD-lopunny-BookSprite.png
BoxSprite: SRD-lopunny-BoxSprite.png
DexCategory: Rabbit Pokemon
DexDescription: "Lopunny is extremely cautious, it quickly bounds off when it senses\
  \ danger. If they are touched roughly, they throw kicks and jump away. Keep the\
  \ fur it sheds as it\u2019s highly valued to make quality yarn."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Buneary]]'
  Stat: Happiness
  Value: 4
- Evolves: To
  Item: Lopunnite
  Kind: Mega
  Pokemon: '[[SRD-Lopunny (Mega Form)]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Limber
HomeSprite: SRD-lopunny-HomeSprite.png
Image: lopunny.png
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
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Return|Return]]'
- - Amateur
  - '[[SRD-Bounce|Bounce]]'
- - Amateur
  - '[[SRD-Rototiller|Rototiller]]'
- - Amateur
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Amateur
  - '[[SRD-Magic Coat|Magic Coat]]'
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
  - '[[SRD-After You|After You]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Ace
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Pro
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
Number: 428
ShuffleToken: SRD-lopunny-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 33.3
  Pounds: 73.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lopunny-BookSprite.png|wsmall]]
> ![[SRD-lopunny-HomeSprite.png]]
> ![[SRD-lopunny-BoxSprite.png|htiny]]
> ![[SRD-lopunny-ShuffleToken.png|wsmall]]


*Rabbit Pokemon*
*Lopunny is extremely cautious, it quickly bounds off when it senses danger. If they are touched roughly, they throw kicks and jump away. Keep the fur it sheds as it’s highly valued to make quality yarn.*

**DexID**:: 0428
**Name**:: Lopunny
**Type**:: Normal
**Abilities**:: [[SRD-Cute Charm|Cute Charm]] / [[SRD-Klutz|Klutz]] ([[SRD-Limber|Limber]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'9" / 1.2m
**Weight**: 73.4lbs / 33.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                     | Kind   | Stat      | Value   | Item      |
|:----------|:----------------------------|:-------|:----------|:--------|:----------|
| From      | [[SRD-Buneary]]             | Stat   | Happiness | 4.0     |           |
| To        | [[SRD-Lopunny (Mega Form)]] | Mega   |           |         | Lopunnite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Lopunny.md"
flatten moves as T
where file.path = this.file.path
```
