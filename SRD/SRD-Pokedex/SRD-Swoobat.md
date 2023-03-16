---
Ability1: Unaware
Ability2: Klutz
BookSprite: SRD-swoobat-BookSprite.png
BoxSprite: SRD-swoobat-BoxSprite.png
DexCategory: Courting Pokemon
DexDescription: They communicate by emitting ultrasonic waves through their noses.
  This sound is not perceived by humans but it can affect their mood and emotions.
  It hunts Bug Pokemon and loves fresh fruit.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Woobat]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Simple
HomeSprite: SRD-swoobat-HomeSprite.png
Image: swoobat.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - Starter
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Heart Stamp|Heart Stamp]]'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Attract|Attract]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Roost|Roost]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 528
ShuffleToken: SRD-swoobat-ShuffleToken.png
Type1: Psychic
Type2: Flying
Weight:
  Kilograms: 10.5
  Pounds: 23.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-swoobat-BookSprite.png|wsmall]]
> ![[SRD-swoobat-HomeSprite.png]]
> ![[SRD-swoobat-BoxSprite.png|htiny]]
> ![[SRD-swoobat-ShuffleToken.png|wsmall]]


*Courting Pokemon*
*They communicate by emitting ultrasonic waves through their noses. This sound is not perceived by humans but it can affect their mood and emotions. It hunts Bug Pokemon and loves fresh fruit.*

**DexID**:: 0528
**Name**:: Swoobat
**Type**:: Psychic / Flying
**Abilities**:: [[SRD-Unaware|Unaware]] / [[SRD-Klutz|Klutz]] ([[SRD-Simple|Simple]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 23.1lbs / 10.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Stat      |   Value |
|:----------|:---------------|:-------|:----------|--------:|
| From      | [[SRD-Woobat]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Swoobat.md"
flatten moves as T
where file.path = this.file.path
```
