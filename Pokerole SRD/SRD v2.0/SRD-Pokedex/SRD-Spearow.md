---
Ability1: Keen Eye
Ability2: ''
BookSprite: SRD-spearow-BookSprite.png
BoxSprite: SRD-spearow-BoxSprite.png
DexCategory: Tiny Bird Pokemon
DexDescription: Lives in flocks on grasslands. Very protective of its territory. It
  flaps its short wings to dart around at high speed. It is a little short-tempered
  - if disturbed, it will shriek, calling its flock for aid.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Fearow]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Sniper
HomeSprite: SRD-spearow-HomeSprite.png
Image: spearow.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Peck|Peck]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Attack|Fury Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Assurance|Assurance]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mirror Move|Mirror Move]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Roost|Roost]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Drill Peck|Drill Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Feather Dance|Feather Dance]]'
Number: 21
ShuffleToken: SRD-spearow-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 2.0
  Pounds: 4.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-spearow-BookSprite.png|wsmall]]
> ![[SRD-spearow-HomeSprite.png]]
> ![[SRD-spearow-BoxSprite.png|htiny]]
> ![[SRD-spearow-ShuffleToken.png|wsmall]]


*Tiny Bird Pokemon*
*Lives in flocks on grasslands. Very protective of its territory. It flaps its short wings to dart around at high speed. It is a little short-tempered - if disturbed, it will shriek, calling its flock for aid.*

**DexID**:: 0021
**Name**:: Spearow
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] ([[SRD-Sniper|Sniper]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 4.4lbs / 2.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Fearow]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Spearow.md"
flatten moves as T
where file.path = this.file.path
```
