---
Ability1: Chlorophyll
Ability2: Solar Power
BookSprite: SRD-sunflora-BookSprite.png
BoxSprite: SRD-sunflora-BoxSprite.png
DexCategory: Sun Pokemon
DexDescription: Sunfloras live in flower patches. They convert solar energy into nutrition
  and are highly active in the warm daytime but suddenly stop moving as soon as the
  sun sets, closing their petals to cover their face.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Sun Stone
  Kind: Stone
  Pokemon: '[[SRD-Sunkern]]'
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Early Bird
HomeSprite: SRD-sunflora-HomeSprite.png
Image: sunflora.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Growth|Growth]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Grass Whistle|Grass Whistle]]'
- - Beginner
  - '[[SRD-Ingrain|Ingrain]]'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flower Shield|Flower Shield]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Worry Seed|Worry Seed]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Petal Dance|Petal Dance]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Ace
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Pro
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 192
ShuffleToken: SRD-sunflora-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 8.5
  Pounds: 18.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sunflora-BookSprite.png|wsmall]]
> ![[SRD-sunflora-HomeSprite.png]]
> ![[SRD-sunflora-BoxSprite.png|htiny]]
> ![[SRD-sunflora-ShuffleToken.png|wsmall]]


*Sun Pokemon*
*Sunfloras live in flower patches. They convert solar energy into nutrition and are highly active in the warm daytime but suddenly stop moving as soon as the sun sets, closing their petals to cover their face.*

**DexID**:: 0192
**Name**:: Sunflora
**Type**:: Grass
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Solar Power|Solar Power]] ([[SRD-Early Bird|Early Bird]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 18.7lbs / 8.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Item      |
|:----------|:----------------|:-------|:----------|
| From      | [[SRD-Sunkern]] | Stone  | Sun Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Sunflora.md"
flatten moves as T
where file.path = this.file.path
```
