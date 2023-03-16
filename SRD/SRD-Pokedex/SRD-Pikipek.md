---
Ability1: Keen Eye
Ability2: Skill Link
BookSprite: SRD-pikipek-BookSprite.png
BoxSprite: SRD-pikipek-BoxSprite.png
DexCategory: Woodpecker Pokemon
DexDescription: "Their beaks are incredibly strong, it takes them a few minutes to\
  \ shatter rock. They eat berries and shoot the seeds to defend themselves. Pikipek\
  \ don\u2019t sing, but communicate with pecking sounds."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Trumbeak]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Pickup
HomeSprite: SRD-pikipek-HomeSprite.png
Image: pikipek.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Drill Peck|Drill Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Ace
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Uproar|Uproar]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[SRD-Mirror Move|Mirror Move]]'
Number: 731
ShuffleToken: SRD-pikipek-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 1.2
  Pounds: 2.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pikipek-BookSprite.png|wsmall]]
> ![[SRD-pikipek-HomeSprite.png]]
> ![[SRD-pikipek-BoxSprite.png|htiny]]
> ![[SRD-pikipek-ShuffleToken.png|wsmall]]


*Woodpecker Pokemon*
*Their beaks are incredibly strong, it takes them a few minutes to shatter rock. They eat berries and shoot the seeds to defend themselves. Pikipek don’t sing, but communicate with pecking sounds.*

**DexID**:: 0731
**Name**:: Pikipek
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Skill Link|Skill Link]] ([[SRD-Pickup|Pickup]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 2.6lbs / 1.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Trumbeak]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Pikipek.md"
flatten moves as T
where file.path = this.file.path
```
