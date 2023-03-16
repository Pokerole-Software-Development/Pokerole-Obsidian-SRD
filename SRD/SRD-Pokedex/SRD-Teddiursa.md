---
Ability1: Pickup
Ability2: Quick Feet
BookSprite: SRD-teddiursa-BookSprite.png
BoxSprite: SRD-teddiursa-BoxSprite.png
DexCategory: Little Bear Pokemon
DexDescription: If they find honey, their crescent moon mark glows. They hoard food
  for winter and concoct their own honey by mixing fruits and pollen collected by
  Beedrills. They live in forests with their mothers.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Ursaring]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Honey Gather
HomeSprite: SRD-teddiursa-HomeSprite.png
Image: teddiursa.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Starter
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Covet|Covet]]'
- - Beginner
  - '[[SRD-Fling|Fling]]'
- - Beginner
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Play Nice|Play Nice]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Snore|Snore]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
- - Pro
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Pro
  - '[[SRD-Yawn|Yawn]]'
Number: 216
ShuffleToken: SRD-teddiursa-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 8.8
  Pounds: 19.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-teddiursa-BookSprite.png|wsmall]]
> ![[SRD-teddiursa-HomeSprite.png]]
> ![[SRD-teddiursa-BoxSprite.png|htiny]]
> ![[SRD-teddiursa-ShuffleToken.png|wsmall]]


*Little Bear Pokemon*
*If they find honey, their crescent moon mark glows. They hoard food for winter and concoct their own honey by mixing fruits and pollen collected by Beedrills. They live in forests with their mothers.*

**DexID**:: 0216
**Name**:: Teddiursa
**Type**:: Normal
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Quick Feet|Quick Feet]] ([[SRD-Honey Gather|Honey Gather]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 19.4lbs / 8.8kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Ursaring]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Teddiursa.md"
flatten moves as T
where file.path = this.file.path
```
