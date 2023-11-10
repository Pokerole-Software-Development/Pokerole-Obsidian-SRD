---
Ability1: Synchronize
Ability2: ''
BookSprite: SRD-umbreon-BookSprite.png
BoxSprite: SRD-umbreon-BoxSprite.png
DexCategory: Moonlight Pokemon
DexDescription: "Umbreon evolved from exposure to the moon\u2019s energy pulses. It\
  \ lurks in darkness and waits for its foes to move. The rings on its body glow when\
  \ it leaps to attack. Its fur is drenched with poison."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Special
  Pokemon: '[[SRD-Eevee]]'
  Special: Moonlight
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Inner Focus
HomeSprite: SRD-umbreon-HomeSprite.png
Image: umbreon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Moonlight|Moonlight]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Guard Swap|Guard Swap]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Curse|Curse]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
Number: 197
ShuffleToken: SRD-umbreon-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 27.0
  Pounds: 59.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-umbreon-BookSprite.png|wsmall]]
> ![[SRD-umbreon-HomeSprite.png]]
> ![[SRD-umbreon-BoxSprite.png|htiny]]
> ![[SRD-umbreon-ShuffleToken.png|wsmall]]


*Moonlight Pokemon*
*Umbreon evolved from exposure to the moon’s energy pulses. It lurks in darkness and waits for its foes to move. The rings on its body glow when it leaps to attack. Its fur is drenched with poison.*

**DexID**:: 0197
**Name**:: Umbreon
**Type**:: Dark
**Abilities**:: [[SRD-Synchronize|Synchronize]] ([[SRD-Inner Focus|Inner Focus]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 3'3" / 1.0m
**Weight**: 59.5lbs / 27.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind    | Stat      |   Value | Special   |
|:----------|:--------------|:--------|:----------|--------:|:----------|
| From      | [[SRD-Eevee]] | Special | Happiness |       4 | Moonlight |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Umbreon.md"
flatten moves as T
where file.path = this.file.path
```
