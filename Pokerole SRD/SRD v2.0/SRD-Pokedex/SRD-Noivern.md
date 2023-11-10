---
Ability1: Frisk
Ability2: Infiltrator
BookSprite: SRD-noivern-BookSprite.png
BoxSprite: SRD-noivern-BoxSprite.png
DexCategory: Sound Wave Pokemon
DexDescription: "They fly during the new moon and attack careless prey. Nothing can\
  \ beat them in a battle in the dark. To keep them calm you should feed them fruit\
  \ or else they\u2019ll release shocking ultrasonic waves."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Noibat]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Telepathy
HomeSprite: SRD-noivern-HomeSprite.png
Image: noivern.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Screech|Screech]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Amateur
  - '[[SRD-Moonlight|Moonlight]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[SRD-Tailwind|Tailwind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - Ace
  - '[[SRD-Boomburst|Boomburst]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Pro
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 715
ShuffleToken: SRD-noivern-ShuffleToken.png
Type1: Flying
Type2: Dragon
Weight:
  Kilograms: 85.0
  Pounds: 187.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-noivern-BookSprite.png|wsmall]]
> ![[SRD-noivern-HomeSprite.png]]
> ![[SRD-noivern-BoxSprite.png|htiny]]
> ![[SRD-noivern-ShuffleToken.png|wsmall]]


*Sound Wave Pokemon*
*They fly during the new moon and attack careless prey. Nothing can beat them in a battle in the dark. To keep them calm you should feed them fruit or else they’ll release shocking ultrasonic waves.*

**DexID**:: 0715
**Name**:: Noivern
**Type**:: Flying / Dragon
**Abilities**:: [[SRD-Frisk|Frisk]] / [[SRD-Infiltrator|Infiltrator]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 187.4lbs / 85.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Noibat]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Noivern.md"
flatten moves as T
where file.path = this.file.path
```
