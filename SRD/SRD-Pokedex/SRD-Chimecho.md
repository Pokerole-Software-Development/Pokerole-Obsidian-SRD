---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-chimecho-BookSprite.png
BoxSprite: SRD-chimecho-BoxSprite.png
DexCategory: Wind Chime Pokemon
DexDescription: They have seven different cries that resound with the wind. They can
  create ultrasonic waves when they are in danger. Using the suction cup on their
  head, they hang to branches on windy days.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Chingling]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: ''
HomeSprite: SRD-chimecho-HomeSprite.png
Image: chimecho.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Wrap|Wrap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Uproar|Uproar]]'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Amateur
  - '[[SRD-Heal Bell|Heal Bell]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Ace
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Recover|Recover]]'
- - Pro
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Pro
  - '[[SRD-Stored Power|Stored Power]]'
Number: 358
ShuffleToken: SRD-chimecho-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 1.0
  Pounds: 2.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-chimecho-BookSprite.png|wsmall]]
> ![[SRD-chimecho-HomeSprite.png]]
> ![[SRD-chimecho-BoxSprite.png|htiny]]
> ![[SRD-chimecho-ShuffleToken.png|wsmall]]


*Wind Chime Pokemon*
*They have seven different cries that resound with the wind. They can create ultrasonic waves when they are in danger. Using the suction cup on their head, they hang to branches on windy days.*

**DexID**:: 0358
**Name**:: Chimecho
**Type**:: Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 2.2lbs / 1.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Stat      |   Value |
|:----------|:------------------|:-------|:----------|--------:|
| From      | [[SRD-Chingling]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Chimecho.md"
flatten moves as T
where file.path = this.file.path
```
