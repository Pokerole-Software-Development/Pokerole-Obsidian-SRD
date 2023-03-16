---
Ability1: Water Absorb
Ability2: Damp
BookSprite: SRD-poliwrath-BookSprite.png
BoxSprite: SRD-poliwrath-BoxSprite.png
DexCategory: Tadpole Pokemon
DexDescription: "It\u2019s not common to find it in the wild. Most sightings take\
  \ place when it is on land. Once he is inside the water, it will swim far away.\
  \ This Pokemon is an outstanding swimmer, capable of beating any human."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Water Stone
  Kind: Stone
  Pokemon: '[[SRD-Poliwhirl]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Swift Swim
HomeSprite: SRD-poliwrath-HomeSprite.png
Image: poliwrath.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[SRD-Circle Throw|Circle Throw]]'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Submission|Submission]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - Ace
  - '[[SRD-Mind Reader|Mind Reader]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
Number: 62
ShuffleToken: SRD-poliwrath-ShuffleToken.png
Type1: Water
Type2: Fighting
Weight:
  Kilograms: 54.0
  Pounds: 119.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-poliwrath-BookSprite.png|wsmall]]
> ![[SRD-poliwrath-HomeSprite.png]]
> ![[SRD-poliwrath-BoxSprite.png|htiny]]
> ![[SRD-poliwrath-ShuffleToken.png|wsmall]]


*Tadpole Pokemon*
*It’s not common to find it in the wild. Most sightings take place when it is on land. Once he is inside the water, it will swim far away. This Pokemon is an outstanding swimmer, capable of beating any human.*

**DexID**:: 0062
**Name**:: Poliwrath
**Type**:: Water / Fighting
**Abilities**:: [[SRD-Water Absorb|Water Absorb]] / [[SRD-Damp|Damp]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 119.0lbs / 54.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Item        |
|:----------|:------------------|:-------|:------------|
| From      | [[SRD-Poliwhirl]] | Stone  | Water Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Poliwrath.md"
flatten moves as T
where file.path = this.file.path
```
