---
Ability1: Guts
Ability2: Quick Feet
BookSprite: SRD-ursaring-BookSprite.png
BoxSprite: SRD-ursaring-BoxSprite.png
DexCategory: Hibernator Pokemon
DexDescription: They are incredibly strong, great climbers and posses an amazing sense
  of smell. They snap trees and feed on their fruit as they eat quite a lot. A forest
  full of scratched trees marks the territory of Ursarings.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Teddiursa]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Unnerve
HomeSprite: SRD-ursaring-HomeSprite.png
Image: ursaring.png
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
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Snore|Snore]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Play Nice|Play Nice]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Gunk Shot|Gunk Shot]]'
Number: 217
ShuffleToken: SRD-ursaring-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 125.8
  Pounds: 277.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ursaring-BookSprite.png|wsmall]]
> ![[SRD-ursaring-HomeSprite.png]]
> ![[SRD-ursaring-BoxSprite.png|htiny]]
> ![[SRD-ursaring-ShuffleToken.png|wsmall]]


*Hibernator Pokemon*
*They are incredibly strong, great climbers and posses an amazing sense of smell. They snap trees and feed on their fruit as they eat quite a lot. A forest full of scratched trees marks the territory of Ursarings.*

**DexID**:: 0217
**Name**:: Ursaring
**Type**:: Normal
**Abilities**:: [[SRD-Guts|Guts]] / [[SRD-Quick Feet|Quick Feet]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 277.3lbs / 125.8kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Teddiursa]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Ursaring.md"
flatten moves as T
where file.path = this.file.path
```
