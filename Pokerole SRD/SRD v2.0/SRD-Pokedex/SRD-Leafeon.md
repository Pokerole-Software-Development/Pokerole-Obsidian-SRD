---
Ability1: Leaf Guard
Ability2: ''
BookSprite: SRD-leafeon-BookSprite.png
BoxSprite: SRD-leafeon-BoxSprite.png
DexCategory: Verdant Pokemon
DexDescription: "Eevee evolves to Leafeon when it\u2019s living near a special kind\
  \ of moss. Its cells are capable of performing photosynthesis. It is a calm Pokemon\
  \ and does not usually fight but its leaves are sharp and strong."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Eevee]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Chlorophyll
HomeSprite: SRD-leafeon-HomeSprite.png
Image: leafeon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Grass Whistle|Grass Whistle]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Flail|Flail]]'
Number: 470
ShuffleToken: SRD-leafeon-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 25.5
  Pounds: 56.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-leafeon-BookSprite.png|wsmall]]
> ![[SRD-leafeon-HomeSprite.png]]
> ![[SRD-leafeon-BoxSprite.png|htiny]]
> ![[SRD-leafeon-ShuffleToken.png|wsmall]]


*Verdant Pokemon*
*Eevee evolves to Leafeon when it’s living near a special kind of moss. Its cells are capable of performing photosynthesis. It is a calm Pokemon and does not usually fight but its leaves are sharp and strong.*

**DexID**:: 0470
**Name**:: Leafeon
**Type**:: Grass
**Abilities**:: [[SRD-Leaf Guard|Leaf Guard]] ([[SRD-Chlorophyll|Chlorophyll]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 56.2lbs / 25.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Item       |
|:----------|:--------------|:-------|:-----------|
| From      | [[SRD-Eevee]] | Stone  | Leaf Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Leafeon.md"
flatten moves as T
where file.path = this.file.path
```
