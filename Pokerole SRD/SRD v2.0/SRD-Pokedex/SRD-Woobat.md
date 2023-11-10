---
Ability1: Unaware
Ability2: Klutz
BookSprite: SRD-woobat-BookSprite.png
BoxSprite: SRD-woobat-BoxSprite.png
DexCategory: Bat Pokemon
DexDescription: It lives in dark forests and caves. Emits ultrasonic waves from its
  nose it learns about its surroundings. The two small eyes it has get covered by
  its own fur. It clings to trees and cave walls to sleep at night.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Swoobat]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Simple
HomeSprite: SRD-woobat-HomeSprite.png
Image: woobat.png
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
Number: 527
ShuffleToken: SRD-woobat-ShuffleToken.png
Type1: Psychic
Type2: Flying
Weight:
  Kilograms: 2.1
  Pounds: 4.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-woobat-BookSprite.png|wsmall]]
> ![[SRD-woobat-HomeSprite.png]]
> ![[SRD-woobat-BoxSprite.png|htiny]]
> ![[SRD-woobat-ShuffleToken.png|wsmall]]


*Bat Pokemon*
*It lives in dark forests and caves. Emits ultrasonic waves from its nose it learns about its surroundings. The two small eyes it has get covered by its own fur. It clings to trees and cave walls to sleep at night.*

**DexID**:: 0527
**Name**:: Woobat
**Type**:: Psychic / Flying
**Abilities**:: [[SRD-Unaware|Unaware]] / [[SRD-Klutz|Klutz]] ([[SRD-Simple|Simple]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 4.6lbs / 2.1kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Stat      |   Value |
|:----------|:----------------|:-------|:----------|--------:|
| To        | [[SRD-Swoobat]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Woobat.md"
flatten moves as T
where file.path = this.file.path
```
