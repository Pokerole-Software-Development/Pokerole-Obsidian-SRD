---
Ability1: Lightning Rod
Ability2: Motor Drive
BookSprite: SRD-blitzle-BookSprite.png
BoxSprite: SRD-blitzle-BoxSprite.png
DexCategory: Electrified Pokemon
DexDescription: When storm clouds cover the plains you can see them running around
  chasing the lightnings to absorb them on their mane. They form big herds and use
  the pattern on their skin to confuse predators.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Zebstrika]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Sap Sipper
HomeSprite: SRD-blitzle-HomeSprite.png
Image: blitzle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Charge|Charge]]'
- - Beginner
  - '[[SRD-Shock Wave|Shock Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Wild Charge|Wild Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Me First|Me First]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Double Kick|Double Kick]]'
Number: 522
ShuffleToken: SRD-blitzle-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 29.8
  Pounds: 65.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-blitzle-BookSprite.png|wsmall]]
> ![[SRD-blitzle-HomeSprite.png]]
> ![[SRD-blitzle-BoxSprite.png|htiny]]
> ![[SRD-blitzle-ShuffleToken.png|wsmall]]


*Electrified Pokemon*
*When storm clouds cover the plains you can see them running around chasing the lightnings to absorb them on their mane. They form big herds and use the pattern on their skin to confuse predators.*

**DexID**:: 0522
**Name**:: Blitzle
**Type**:: Electric
**Abilities**:: [[SRD-Lightning Rod|Lightning Rod]] / [[SRD-Motor Drive|Motor Drive]] ([[SRD-Sap Sipper|Sap Sipper]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'6" / 0.8m
**Weight**: 65.7lbs / 29.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Zebstrika]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Blitzle.md"
flatten moves as T
where file.path = this.file.path
```
