---
Ability1: Cute Charm
Ability2: Technician
BookSprite: SRD-minccino-BookSprite.png
BoxSprite: SRD-minccino-BoxSprite.png
DexCategory: Chinchilla Pokemon
DexDescription: They greet one another by rubbing their tails, which are always kept
  well groomed and clean. Housewives love to keep them as pets because they eagerly
  help to clean the house.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Shiny Stone
  Kind: Stone
  Pokemon: '[[SRD-Cinccino]]'
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Skill Link
HomeSprite: SRD-minccino-HomeSprite.png
Image: minccino.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Beginner
  - '[[SRD-Tickle|Tickle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Tail Slap|Tail Slap]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Amateur
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Slam|Slam]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-After You|After You]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
Number: 572
ShuffleToken: SRD-minccino-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 5.8
  Pounds: 12.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-minccino-BookSprite.png|wsmall]]
> ![[SRD-minccino-HomeSprite.png]]
> ![[SRD-minccino-BoxSprite.png|htiny]]
> ![[SRD-minccino-ShuffleToken.png|wsmall]]


*Chinchilla Pokemon*
*They greet one another by rubbing their tails, which are always kept well groomed and clean. Housewives love to keep them as pets because they eagerly help to clean the house.*

**DexID**:: 0572
**Name**:: Minccino
**Type**:: Normal
**Abilities**:: [[SRD-Cute Charm|Cute Charm]] / [[SRD-Technician|Technician]] ([[SRD-Skill Link|Skill Link]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 12.8lbs / 5.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| To        | [[SRD-Cinccino]] | Stone  | Shiny Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Minccino.md"
flatten moves as T
where file.path = this.file.path
```
