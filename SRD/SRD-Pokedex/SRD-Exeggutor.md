---
Ability1: Chlorophyll
Ability2: ''
BookSprite: SRD-exeggutor-BookSprite.png
BoxSprite: SRD-exeggutor-BoxSprite.png
DexCategory: Coconut Pokemon
DexDescription: Originally from tropical areas. Exeggutor's heads grow larger with
  strong sunlight. Each head thinks independently. They are friendly and provide their
  shade to other Pokemon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Exeggcute]]'
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Harvest
HomeSprite: SRD-exeggutor-HomeSprite.png
Image: exeggutor.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Barrage|Barrage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Psyshock|Psyshock]]'
- - Amateur
  - '[[SRD-Egg Bomb|Egg Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Nightmare|Nightmare]]'
- - Pro
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Pro
  - '[[SRD-Curse|Curse]]'
Number: 103
ShuffleToken: SRD-exeggutor-ShuffleToken.png
Type1: Grass
Type2: Psychic
Weight:
  Kilograms: 120.0
  Pounds: 264.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-exeggutor-BookSprite.png|wsmall]]
> ![[SRD-exeggutor-HomeSprite.png]]
> ![[SRD-exeggutor-BoxSprite.png|htiny]]
> ![[SRD-exeggutor-ShuffleToken.png|wsmall]]


*Coconut Pokemon*
*Originally from tropical areas. Exeggutor's heads grow larger with strong sunlight. Each head thinks independently. They are friendly and provide their shade to other Pokemon.*

**DexID**:: 0103
**Name**:: Exeggutor
**Type**:: Grass / Psychic
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Harvest|Harvest]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 264.6lbs / 120.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Item       |
|:----------|:------------------|:-------|:-----------|
| From      | [[SRD-Exeggcute]] | Stone  | Leaf Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Exeggutor.md"
flatten moves as T
where file.path = this.file.path
```
