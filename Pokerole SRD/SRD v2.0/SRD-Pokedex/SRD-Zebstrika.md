---
Ability1: Lightning Rod
Ability2: Motor Drive
BookSprite: SRD-zebstrika-BookSprite.png
BoxSprite: SRD-zebstrika-BoxSprite.png
DexCategory: Thunderbolt Pokemon
DexDescription: "It is very ill tempered and wild, there have been very few cases\
  \ of it being successfully tamed. It can shoot lightning from it\u2019s mane in\
  \ all directions. If you try to mount it without warning it will shock you."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Blitzle]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Sap Sipper
HomeSprite: SRD-zebstrika-HomeSprite.png
Image: zebstrika.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Beginner
  - '[[SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Ion Deluge|Ion Deluge]]'
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
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Double Kick|Double Kick]]'
- - Pro
  - '[[SRD-Screech|Screech]]'
Number: 523
ShuffleToken: SRD-zebstrika-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 79.5
  Pounds: 175.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zebstrika-BookSprite.png|wsmall]]
> ![[SRD-zebstrika-HomeSprite.png]]
> ![[SRD-zebstrika-BoxSprite.png|htiny]]
> ![[SRD-zebstrika-ShuffleToken.png|wsmall]]


*Thunderbolt Pokemon*
*It is very ill tempered and wild, there have been very few cases of it being successfully tamed. It can shoot lightning from it’s mane in all directions. If you try to mount it without warning it will shock you.*

**DexID**:: 0523
**Name**:: Zebstrika
**Type**:: Electric
**Abilities**:: [[SRD-Lightning Rod|Lightning Rod]] / [[SRD-Motor Drive|Motor Drive]] ([[SRD-Sap Sipper|Sap Sipper]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'2" / 1.6m
**Weight**: 175.3lbs / 79.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Blitzle]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zebstrika.md"
flatten moves as T
where file.path = this.file.path
```
