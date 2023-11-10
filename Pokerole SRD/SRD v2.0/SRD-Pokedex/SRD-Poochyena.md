---
Ability1: Run Away
Ability2: Quick Feet
BookSprite: SRD-poochyena-BookSprite.png
BoxSprite: SRD-poochyena-BoxSprite.png
DexCategory: Bite Pokemon
DexDescription: Poochyena will bite anything that moves. They will chase people and
  other Pokemon for dozens of miles without loosing track. This Pokemon is persistent
  and tenacious. In the wild, they form small hunting packs.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Mightyena]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Rattled
HomeSprite: SRD-poochyena-HomeSprite.png
Image: poochyena.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Howl|Howl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Embargo|Embargo]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dig|Dig]]'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 261
ShuffleToken: SRD-poochyena-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 13.6
  Pounds: 30.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-poochyena-BookSprite.png|wsmall]]
> ![[SRD-poochyena-HomeSprite.png]]
> ![[SRD-poochyena-BoxSprite.png|htiny]]
> ![[SRD-poochyena-ShuffleToken.png|wsmall]]


*Bite Pokemon*
*Poochyena will bite anything that moves. They will chase people and other Pokemon for dozens of miles without loosing track. This Pokemon is persistent and tenacious. In the wild, they form small hunting packs.*

**DexID**:: 0261
**Name**:: Poochyena
**Type**:: Dark
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Quick Feet|Quick Feet]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 30.0lbs / 13.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Mightyena]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Poochyena.md"
flatten moves as T
where file.path = this.file.path
```
