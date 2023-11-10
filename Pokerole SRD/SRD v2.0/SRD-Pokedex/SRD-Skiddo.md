---
Ability1: Sap Sipper
Ability2: ''
BookSprite: SRD-skiddo-BookSprite.png
BoxSprite: SRD-skiddo-BoxSprite.png
DexCategory: Mount Pokemon
DexDescription: "It\u2019s thought to be one of the first Pokemon to live in harmony\
  \ with humans. If it has sunshine and water it doesn\u2019t need to eat - the leaves\
  \ on its back will produce the energy for it."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Gogoat]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Grass Pelt
HomeSprite: SRD-skiddo-HomeSprite.png
Image: skiddo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Worry Seed|Worry Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Horn Leech|Horn Leech]]'
- - Ace
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Ace
  - '[[SRD-Milk Drink|Milk Drink]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Defense Curl|Defense Curl]]'
Number: 672
ShuffleToken: SRD-skiddo-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 31.0
  Pounds: 68.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-skiddo-BookSprite.png|wsmall]]
> ![[SRD-skiddo-HomeSprite.png]]
> ![[SRD-skiddo-BoxSprite.png|htiny]]
> ![[SRD-skiddo-ShuffleToken.png|wsmall]]


*Mount Pokemon*
*It’s thought to be one of the first Pokemon to live in harmony with humans. If it has sunshine and water it doesn’t need to eat - the leaves on its back will produce the energy for it.*

**DexID**:: 0672
**Name**:: Skiddo
**Type**:: Grass
**Abilities**:: [[SRD-Sap Sipper|Sap Sipper]] ([[SRD-Grass Pelt|Grass Pelt]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 68.3lbs / 31.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Gogoat]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Skiddo.md"
flatten moves as T
where file.path = this.file.path
```
