---
Ability1: Keen Eye
Ability2: Tangled Feet
BookSprite: SRD-pidgey-BookSprite.png
BoxSprite: SRD-pidgey-BoxSprite.png
DexCategory: Tiny Bird Pokemon
DexDescription: "Very common around the world, it prefers to live in forests but can\
  \ be seen around cities and plains too. It\u2019s a docile Pokemon that tends to\
  \ avoid trouble. It flaps its wings to lure prey out of hiding."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Pidgeotto]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Big Pecks
HomeSprite: SRD-pidgey-HomeSprite.png
Image: pidgey.png
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
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Pro
  - '[[SRD-Uproar|Uproar]]'
- - Pro
  - '[[SRD-Steel Wing|Steel Wing]]'
Number: 16
ShuffleToken: SRD-pidgey-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 1.8
  Pounds: 4.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pidgey-BookSprite.png|wsmall]]
> ![[SRD-pidgey-HomeSprite.png]]
> ![[SRD-pidgey-BoxSprite.png|htiny]]
> ![[SRD-pidgey-ShuffleToken.png|wsmall]]


*Tiny Bird Pokemon*
*Very common around the world, it prefers to live in forests but can be seen around cities and plains too. It’s a docile Pokemon that tends to avoid trouble. It flaps its wings to lure prey out of hiding.*

**DexID**:: 0016
**Name**:: Pidgey
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Tangled Feet|Tangled Feet]] ([[SRD-Big Pecks|Big Pecks]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 4.0lbs / 1.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Pidgeotto]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Pidgey.md"
flatten moves as T
where file.path = this.file.path
```
