---
Ability1: Keen Eye
Ability2: Tangled Feet
BookSprite: SRD-pidgeotto-BookSprite.png
BoxSprite: SRD-pidgeotto-BoxSprite.png
DexCategory: Bird Pokemon
DexDescription: Each Pidgeotto claims a large meadow area as its territory. This Pokemon
  flies around, patrolling its home and will attack any intruders with its sharp claws.
  It will challenge itself to fly a bit higher every day.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Pidgey]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Pidgeot]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Big Pecks
HomeSprite: SRD-pidgeotto-HomeSprite.png
Image: pidgeotto.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Gust|Gust]]'
- - Beginner
  - '[[SRD-Twister|Twister]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Amateur
  - '[[SRD-Mirror Move|Mirror Move]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - Ace
  - '[[SRD-Roost|Roost]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Uproar|Uproar]]'
- - Pro
  - '[[SRD-Steel Wing|Steel Wing]]'
Number: 17
ShuffleToken: SRD-pidgeotto-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 30.0
  Pounds: 66.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pidgeotto-BookSprite.png|wsmall]]
> ![[SRD-pidgeotto-HomeSprite.png]]
> ![[SRD-pidgeotto-BoxSprite.png|htiny]]
> ![[SRD-pidgeotto-ShuffleToken.png|wsmall]]


*Bird Pokemon*
*Each Pidgeotto claims a large meadow area as its territory. This Pokemon flies around, patrolling its home and will attack any intruders with its sharp claws. It will challenge itself to fly a bit higher every day.*

**DexID**:: 0017
**Name**:: Pidgeotto
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Tangled Feet|Tangled Feet]] ([[SRD-Big Pecks|Big Pecks]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 66.1lbs / 30.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Pidgey]]  | Level  | Medium  |
| To        | [[SRD-Pidgeot]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pidgeotto.md"
flatten moves as T
where file.path = this.file.path
```
