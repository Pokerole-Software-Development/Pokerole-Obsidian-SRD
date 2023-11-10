---
Ability1: Chlorophyll
Ability2: ''
BookSprite: SRD-weepinbell-BookSprite.png
BoxSprite: SRD-weepinbell-BoxSprite.png
DexCategory: Flycatcher Pokemon
DexDescription: It sprays its stun powder to immobilize a prey coming close to it,
  then eats it calmly. If the prey is bigger than itself, it uses its sharp leaves
  to slice it into smaller pieces. Beware of the toxic liquid in its mouth.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Bellsprout]]'
  Speed: Medium
- Evolves: To
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Victreebel]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Gluttony
HomeSprite: SRD-weepinbell-HomeSprite.png
Image: weepinbell.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Vine Whip|Vine Whip]]'
- - Starter
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Wrap|Wrap]]'
- - Beginner
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Acid|Acid]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Slam|Slam]]'
- - Ace
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ingrain|Ingrain]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
- - Pro
  - '[[SRD-Weather Ball|Weather Ball]]'
Number: 70
ShuffleToken: SRD-weepinbell-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 6.4
  Pounds: 14.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-weepinbell-BookSprite.png|wsmall]]
> ![[SRD-weepinbell-HomeSprite.png]]
> ![[SRD-weepinbell-BoxSprite.png|htiny]]
> ![[SRD-weepinbell-ShuffleToken.png|wsmall]]


*Flycatcher Pokemon*
*It sprays its stun powder to immobilize a prey coming close to it, then eats it calmly. If the prey is bigger than itself, it uses its sharp leaves to slice it into smaller pieces. Beware of the toxic liquid in its mouth.*

**DexID**:: 0070
**Name**:: Weepinbell
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Gluttony|Gluttony]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 14.1lbs / 6.4kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   | Item       |
|:----------|:-------------------|:-------|:--------|:-----------|
| From      | [[SRD-Bellsprout]] | Level  | Medium  |            |
| To        | [[SRD-Victreebel]] | Stone  |         | Leaf Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Weepinbell.md"
flatten moves as T
where file.path = this.file.path
```
