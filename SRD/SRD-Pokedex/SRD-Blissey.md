---
Ability1: Natural Cure
Ability2: Serene Grace
BookSprite: SRD-blissey-BookSprite.png
BoxSprite: SRD-blissey-BoxSprite.png
DexCategory: Happiness Pokemon
DexDescription: "Whoever takes a bite on a Blissey's egg becomes loving and caring\
  \ to everyone. They are compassionate, healing anyone who\u2019s injured. Their\
  \ presence makes everyone smile. An intelligent and emphatic Pokemon."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Chansey]]'
  Stat: Happiness
  Value: 5
GenderType: F
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Healer
HomeSprite: SRD-blissey-HomeSprite.png
Image: blissey.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - Beginner
  - '[[SRD-Refresh|Refresh]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bestow|Bestow]]'
- - Amateur
  - '[[SRD-Soft Boiled|Soft Boiled]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Egg Bomb|Egg Bomb]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
- - Pro
  - '[[SRD-Metronome|Metronome]]'
Number: 242
ShuffleToken: SRD-blissey-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 46.8
  Pounds: 103.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-blissey-BookSprite.png|wsmall]]
> ![[SRD-blissey-HomeSprite.png]]
> ![[SRD-blissey-BoxSprite.png|htiny]]
> ![[SRD-blissey-ShuffleToken.png|wsmall]]


*Happiness Pokemon*
*Whoever takes a bite on a Blissey's egg becomes loving and caring to everyone. They are compassionate, healing anyone who’s injured. Their presence makes everyone smile. An intelligent and emphatic Pokemon.*

**DexID**:: 0242
**Name**:: Blissey
**Type**:: Normal
**Abilities**:: [[SRD-Natural Cure|Natural Cure]] / [[SRD-Serene Grace|Serene Grace]] ([[SRD-Healer|Healer]])
**Base HP**:: 12

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::2)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::2)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 4'9" / 1.5m
**Weight**: 103.2lbs / 46.8kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Stat      |   Value |
|:----------|:----------------|:-------|:----------|--------:|
| From      | [[SRD-Chansey]] | Stat   | Happiness |       5 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Blissey.md"
flatten moves as T
where file.path = this.file.path
```
