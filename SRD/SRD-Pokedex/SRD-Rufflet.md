---
Ability1: Keen Eye
Ability2: Sheer Force
BookSprite: SRD-rufflet-BookSprite.png
BoxSprite: SRD-rufflet-BoxSprite.png
DexCategory: Eaglet Pokemon
DexDescription: This species only has males. They are independent from the moment
  they hatch. They will challenge even strong opponents, without fear. Their frequent
  fights help them become stronger.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Braviary]]'
  Speed: Slow
GenderType: M
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Hustle
HomeSprite: SRD-rufflet-HomeSprite.png
Image: rufflet.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Defog|Defog]]'
- - Amateur
  - '[[SRD-Tailwind|Tailwind]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Crush Claw|Crush Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sky Drop|Sky Drop]]'
- - Ace
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Pluck|Pluck]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 627
ShuffleToken: SRD-rufflet-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 10.5
  Pounds: 23.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rufflet-BookSprite.png|wsmall]]
> ![[SRD-rufflet-HomeSprite.png]]
> ![[SRD-rufflet-BoxSprite.png|htiny]]
> ![[SRD-rufflet-ShuffleToken.png|wsmall]]


*Eaglet Pokemon*
*This species only has males. They are independent from the moment they hatch. They will challenge even strong opponents, without fear. Their frequent fights help them become stronger.*

**DexID**:: 0627
**Name**:: Rufflet
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Sheer Force|Sheer Force]] ([[SRD-Hustle|Hustle]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 23.1lbs / 10.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Braviary]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Rufflet.md"
flatten moves as T
where file.path = this.file.path
```
