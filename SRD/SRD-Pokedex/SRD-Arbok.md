---
Ability1: Intimidate
Ability2: Shed Skin
BookSprite: SRD-arbok-BookSprite.png
BoxSprite: SRD-arbok-BoxSprite.png
DexCategory: Cobra Pokemon
DexDescription: This Pokemon has an incredibly strong constricting power. Once it
  wraps its body around its foe, escaping is almost impossible. The pattern on its
  body glows in the dark like a terrifying face.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Ekans]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 11.5
  Meters: 3.5
HiddenAbility: Unnerve
HomeSprite: SRD-arbok-HomeSprite.png
Image: arbok.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Wrap|Wrap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Beginner
  - '[[SRD-Glare|Glare]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Acid|Acid]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - Amateur
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Haze|Haze]]'
- - Ace
  - '[[SRD-Coil|Coil]]'
- - Ace
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Ace
  - '[[SRD-Spite|Spite]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
Number: 24
ShuffleToken: SRD-arbok-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 65.0
  Pounds: 143.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-arbok-BookSprite.png|wsmall]]
> ![[SRD-arbok-HomeSprite.png]]
> ![[SRD-arbok-BoxSprite.png|htiny]]
> ![[SRD-arbok-ShuffleToken.png|wsmall]]


*Cobra Pokemon*
*This Pokemon has an incredibly strong constricting power. Once it wraps its body around its foe, escaping is almost impossible. The pattern on its body glows in the dark like a terrifying face.*

**DexID**:: 0024
**Name**:: Arbok
**Type**:: Poison
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Shed Skin|Shed Skin]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 11'5" / 3.5m
**Weight**: 143.3lbs / 65.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| From      | [[SRD-Ekans]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Arbok.md"
flatten moves as T
where file.path = this.file.path
```
