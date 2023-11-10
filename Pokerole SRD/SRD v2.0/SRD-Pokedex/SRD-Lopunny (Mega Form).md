---
Ability1: Scrappy
Ability2: ''
BookSprite: SRD-lopunny-mega-form-BookSprite.png
BoxSprite: SRD-lopunny-mega-form-BoxSprite.png
DexCategory: Rabbit Pokemon
DexDescription: The power of the Mega Stone awakens its combative nature. Most of
  its fur is lost due to constant fighting, even its ears are used as weapons, whipping
  foes with heavy hits.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Lopunnite
  Kind: Mega
  Pokemon: '[[SRD-Lopunny]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: ''
HomeSprite: SRD-lopunny-mega-form-HomeSprite.png
Image: lopunny-mega-form.png
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
ShuffleToken: SRD-lopunny-mega-form-ShuffleToken.png
Type1: Normal
Type2: Fighting
Weight:
  Kilograms: 28.3
  Pounds: 62.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lopunny-mega-form-BookSprite.png|wsmall]]
> ![[SRD-lopunny-mega-form-HomeSprite.png]]
> ![[SRD-lopunny-mega-form-BoxSprite.png|htiny]]
> ![[SRD-lopunny-mega-form-ShuffleToken.png|wsmall]]


*Rabbit Pokemon*
*The power of the Mega Stone awakens its combative nature. Most of its fur is lost due to constant fighting, even its ears are used as weapons, whipping foes with heavy hits.*

**DexID**:: 0428M1
**Name**:: Lopunny (Mega Form)
**Type**:: Normal / Fighting
**Abilities**:: [[SRD-Scrappy|Scrappy]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'3" / 1.3m
**Weight**: 62.4lbs / 28.3kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Item      |
|:----------|:----------------|:-------|:----------|
| From      | [[SRD-Lopunny]] | Mega   | Lopunnite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Lopunny (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
