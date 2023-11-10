---
Ability1: Cute Charm
Ability2: Magic Guard
BookSprite: SRD-cleffa-BookSprite.png
BoxSprite: SRD-cleffa-BoxSprite.png
DexCategory: Star Shape Pokemon
DexDescription: An extremely elusive Pokemon. A few have appeared when the night skies
  are filled with shooting stars - but they always disappear at dawn. Friendship and
  love allows it to go into the next step of life.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Clefairy]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Friend Guard
HomeSprite: SRD-cleffa-HomeSprite.png
Image: cleffa.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - Beginner
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Tickle|Tickle]]'
- - Amateur
  - '[[SRD-Fake Tears|Fake Tears]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
Number: 173
ShuffleToken: SRD-cleffa-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 3.0
  Pounds: 6.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cleffa-BookSprite.png|wsmall]]
> ![[SRD-cleffa-HomeSprite.png]]
> ![[SRD-cleffa-BoxSprite.png|htiny]]
> ![[SRD-cleffa-ShuffleToken.png|wsmall]]


*Star Shape Pokemon*
*An extremely elusive Pokemon. A few have appeared when the night skies are filled with shooting stars - but they always disappear at dawn. Friendship and love allows it to go into the next step of life.*

**DexID**:: 0173
**Name**:: Cleffa
**Type**:: Fairy
**Abilities**:: [[SRD-Cute Charm|Cute Charm]] / [[SRD-Magic Guard|Magic Guard]] ([[SRD-Friend Guard|Friend Guard]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 6.6lbs / 3.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Stat      |   Value |
|:----------|:-----------------|:-------|:----------|--------:|
| To        | [[SRD-Clefairy]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cleffa.md"
flatten moves as T
where file.path = this.file.path
```
