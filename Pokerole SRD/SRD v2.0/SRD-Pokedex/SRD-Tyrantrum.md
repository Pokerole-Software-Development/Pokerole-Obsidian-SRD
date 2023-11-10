---
Ability1: Strong Jaw
Ability2: ''
BookSprite: SRD-tyrantrum-BookSprite.png
BoxSprite: SRD-tyrantrum-BoxSprite.png
DexCategory: Despot Pokemon
DexDescription: Nothing could stop this Pokemon 100 million years ago, it was a prehistoric
  king. Thanks to its giant jaws, which could shred thick metal plates as if they
  were paper, this Pokemon takes orders from no one.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Tyrunt]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 8.2
  Meters: 2.5
HiddenAbility: Rock Head
HomeSprite: SRD-tyrantrum-HomeSprite.png
Image: tyrantrum.png
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
- - Amateur
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Horn Drill|Horn Drill]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 697
ShuffleToken: SRD-tyrantrum-ShuffleToken.png
Type1: Rock
Type2: Dragon
Weight:
  Kilograms: 270.0
  Pounds: 595.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tyrantrum-BookSprite.png|wsmall]]
> ![[SRD-tyrantrum-HomeSprite.png]]
> ![[SRD-tyrantrum-BoxSprite.png|htiny]]
> ![[SRD-tyrantrum-ShuffleToken.png|wsmall]]


*Despot Pokemon*
*Nothing could stop this Pokemon 100 million years ago, it was a prehistoric king. Thanks to its giant jaws, which could shred thick metal plates as if they were paper, this Pokemon takes orders from no one.*

**DexID**:: 0697
**Name**:: Tyrantrum
**Type**:: Rock / Dragon
**Abilities**:: [[SRD-Strong Jaw|Strong Jaw]] ([[SRD-Rock Head|Rock Head]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 8'2" / 2.5m
**Weight**: 595.2lbs / 270.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Tyrunt]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tyrantrum.md"
flatten moves as T
where file.path = this.file.path
```
