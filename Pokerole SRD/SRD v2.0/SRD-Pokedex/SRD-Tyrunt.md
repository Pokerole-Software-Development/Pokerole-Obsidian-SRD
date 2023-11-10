---
Ability1: Strong Jaw
Ability2: ''
BookSprite: SRD-tyrunt-BookSprite.png
BoxSprite: SRD-tyrunt-BoxSprite.png
DexCategory: Royal Heir Pokemon
DexDescription: "This Pokemon was restored from a fossil. If something happens that\
  \ it doesn\u2019t like, it throws a tantrum and runs wild. Many of the researchers\
  \ that brought it back were attacked by its powerful jaws."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Tyrantrum]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Sturdy
HomeSprite: SRD-tyrunt-HomeSprite.png
Image: tyrunt.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Roar|Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Stomp|Stomp]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Horn Drill|Horn Drill]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Pro
  - '[[SRD-Ice Fang|Ice Fang]]'
Number: 696
ShuffleToken: SRD-tyrunt-ShuffleToken.png
Type1: Rock
Type2: Dragon
Weight:
  Kilograms: 26.0
  Pounds: 57.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tyrunt-BookSprite.png|wsmall]]
> ![[SRD-tyrunt-HomeSprite.png]]
> ![[SRD-tyrunt-BoxSprite.png|htiny]]
> ![[SRD-tyrunt-ShuffleToken.png|wsmall]]


*Royal Heir Pokemon*
*This Pokemon was restored from a fossil. If something happens that it doesn’t like, it throws a tantrum and runs wild. Many of the researchers that brought it back were attacked by its powerful jaws.*

**DexID**:: 0696
**Name**:: Tyrunt
**Type**:: Rock / Dragon
**Abilities**:: [[SRD-Strong Jaw|Strong Jaw]] ([[SRD-Sturdy|Sturdy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 57.3lbs / 26.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Tyrantrum]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tyrunt.md"
flatten moves as T
where file.path = this.file.path
```
