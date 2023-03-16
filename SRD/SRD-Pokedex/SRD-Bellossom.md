---
Ability1: Chlorophyll
Ability2: ''
BookSprite: SRD-bellossom-BookSprite.png
BoxSprite: SRD-bellossom-BoxSprite.png
DexCategory: Flower Pokemon
DexDescription: They are plentiful in tropical areas. The beauty of the flowers on
  its head depends on how stinky it was as a Gloom. Lots of sunshine will make the
  skirt leaves swirl in a beautiful and rhythmic dance.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Sun Stone
  Kind: Stone
  Pokemon: '[[SRD-Gloom]]'
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Healer
HomeSprite: SRD-bellossom-HomeSprite.png
Image: bellossom.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Beginner
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Pro
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Number: 182
ShuffleToken: SRD-bellossom-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 5.8
  Pounds: 12.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bellossom-BookSprite.png|wsmall]]
> ![[SRD-bellossom-HomeSprite.png]]
> ![[SRD-bellossom-BoxSprite.png|htiny]]
> ![[SRD-bellossom-ShuffleToken.png|wsmall]]


*Flower Pokemon*
*They are plentiful in tropical areas. The beauty of the flowers on its head depends on how stinky it was as a Gloom. Lots of sunshine will make the skirt leaves swirl in a beautiful and rhythmic dance.*

**DexID**:: 0182
**Name**:: Bellossom
**Type**:: Grass
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Healer|Healer]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 1'3" / 0.4m
**Weight**: 12.8lbs / 5.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Item      |
|:----------|:--------------|:-------|:----------|
| From      | [[SRD-Gloom]] | Stone  | Sun Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Bellossom.md"
flatten moves as T
where file.path = this.file.path
```
