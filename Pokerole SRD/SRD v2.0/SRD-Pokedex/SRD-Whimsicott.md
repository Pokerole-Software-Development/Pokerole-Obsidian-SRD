---
Ability1: Prankster
Ability2: Infiltrator
BookSprite: SRD-whimsicott-BookSprite.png
BoxSprite: SRD-whimsicott-BoxSprite.png
DexCategory: Windveiled Pokemon
DexDescription: Riding whirlwinds, they appear and disappear. These Pokemon sneak
  through even the smallest gaps into houses and cause all sorts of mischief the balls
  of white fluff it leaves behind reveal its presence.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Sun Stone
  Kind: Stone
  Pokemon: '[[SRD-Cottonee]]'
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Chlorophyll
HomeSprite: SRD-whimsicott-HomeSprite.png
Image: whimsicott.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growth|Growth]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leech Seed|Leech Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mega Drain|Mega Drain]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Cotton Spore|Cotton Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gust|Gust]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tailwind|Tailwind]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Moonblast|Moonblast]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Memento|Memento]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Encore|Encore]]'
Number: 547
ShuffleToken: SRD-whimsicott-ShuffleToken.png
Type1: Grass
Type2: Fairy
Weight:
  Kilograms: 6.6
  Pounds: 14.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-whimsicott-BookSprite.png|wsmall]]
> ![[SRD-whimsicott-HomeSprite.png]]
> ![[SRD-whimsicott-BoxSprite.png|htiny]]
> ![[SRD-whimsicott-ShuffleToken.png|wsmall]]


*Windveiled Pokemon*
*Riding whirlwinds, they appear and disappear. These Pokemon sneak through even the smallest gaps into houses and cause all sorts of mischief the balls of white fluff it leaves behind reveal its presence.*

**DexID**:: 0547
**Name**:: Whimsicott
**Type**:: Grass / Fairy
**Abilities**:: [[SRD-Prankster|Prankster]] / [[SRD-Infiltrator|Infiltrator]] ([[SRD-Chlorophyll|Chlorophyll]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 14.6lbs / 6.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Item      |
|:----------|:-----------------|:-------|:----------|
| From      | [[SRD-Cottonee]] | Stone  | Sun Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Whimsicott.md"
flatten moves as T
where file.path = this.file.path
```
