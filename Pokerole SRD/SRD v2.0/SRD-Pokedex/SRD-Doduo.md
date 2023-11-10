---
Ability1: Run Away
Ability2: Early Bird
BookSprite: SRD-doduo-BookSprite.png
BoxSprite: SRD-doduo-BoxSprite.png
DexCategory: Twin Bird Pokemon
DexDescription: It can fly, but it prefers to run in the prairies. The two heads usually
  get along. While one is eating or sleeping, the other one is alert for predators.
  It is known that they share a brain and their ideas are connected.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dodrio]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Tangled Feet
HomeSprite: SRD-doduo-HomeSprite.png
Image: doduo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - Amateur
  - '[[SRD-Uproar|Uproar]]'
- - Amateur
  - '[[SRD-Acupressure|Acupressure]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Jump Kick|Jump Kick]]'
- - Ace
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mirror Move|Mirror Move]]'
- - Pro
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Pro
  - '[[SRD-Brave Bird|Brave Bird]]'
Number: 84
ShuffleToken: SRD-doduo-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 39.2
  Pounds: 86.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-doduo-BookSprite.png|wsmall]]
> ![[SRD-doduo-HomeSprite.png]]
> ![[SRD-doduo-BoxSprite.png|htiny]]
> ![[SRD-doduo-ShuffleToken.png|wsmall]]


*Twin Bird Pokemon*
*It can fly, but it prefers to run in the prairies. The two heads usually get along. While one is eating or sleeping, the other one is alert for predators. It is known that they share a brain and their ideas are connected.*

**DexID**:: 0084
**Name**:: Doduo
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Early Bird|Early Bird]] ([[SRD-Tangled Feet|Tangled Feet]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 4'6" / 1.4m
**Weight**: 86.4lbs / 39.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Dodrio]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Doduo.md"
flatten moves as T
where file.path = this.file.path
```
