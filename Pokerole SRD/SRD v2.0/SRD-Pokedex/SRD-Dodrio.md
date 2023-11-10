---
Ability1: Run Away
Ability2: Early Bird
BookSprite: SRD-dodrio-BookSprite.png
BoxSprite: SRD-dodrio-BoxSprite.png
DexCategory: Triple Bird Pokemon
DexDescription: A third head comes to change the dynamic the two original had. It
  is common to see the three heads fighting. Each one has its own personality, but
  when they work as a team they can be very powerful.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Doduo]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Tangled Feet
HomeSprite: SRD-dodrio-HomeSprite.png
Image: dodrio.png
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
  - '[[SRD-Tri Attack|Tri Attack]]'
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
Number: 85
ShuffleToken: SRD-dodrio-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 85.2
  Pounds: 187.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dodrio-BookSprite.png|wsmall]]
> ![[SRD-dodrio-HomeSprite.png]]
> ![[SRD-dodrio-BoxSprite.png|htiny]]
> ![[SRD-dodrio-ShuffleToken.png|wsmall]]


*Triple Bird Pokemon*
*A third head comes to change the dynamic the two original had. It is common to see the three heads fighting. Each one has its own personality, but when they work as a team they can be very powerful.*

**DexID**:: 0085
**Name**:: Dodrio
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Early Bird|Early Bird]] ([[SRD-Tangled Feet|Tangled Feet]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'9" / 1.8m
**Weight**: 187.8lbs / 85.2kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| From      | [[SRD-Doduo]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dodrio.md"
flatten moves as T
where file.path = this.file.path
```
