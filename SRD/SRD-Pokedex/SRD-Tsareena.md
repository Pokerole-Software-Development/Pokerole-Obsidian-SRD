---
Ability1: Leaf Guard
Ability2: Queenly Majesty
BookSprite: SRD-tsareena-BookSprite.png
BoxSprite: SRD-tsareena-BoxSprite.png
DexCategory: Fruit Pokemon
DexDescription: Tsareena's elegant appearance is only matched by its boastful fight
  spirit. It is known for disobeying any Trainer giving it orders it dislikes, and
  will celebrate its victories by kicking its defeated foes while laughing.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Steenee]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Sweet Veil
HomeSprite: SRD-tsareena-HomeSprite.png
Image: tsareena.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - Starter
  - '[[SRD-Swagger|Swagger]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Trop Kick|Trop Kick]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Ace
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Pro
  - '[[SRD-Low Sweep|Low Sweep]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
Number: 763
ShuffleToken: SRD-tsareena-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 21.4
  Pounds: 47.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tsareena-BookSprite.png|wsmall]]
> ![[SRD-tsareena-HomeSprite.png]]
> ![[SRD-tsareena-BoxSprite.png|htiny]]
> ![[SRD-tsareena-ShuffleToken.png|wsmall]]


*Fruit Pokemon*
*Tsareena's elegant appearance is only matched by its boastful fight spirit. It is known for disobeying any Trainer giving it orders it dislikes, and will celebrate its victories by kicking its defeated foes while laughing.*

**DexID**:: 0763
**Name**:: Tsareena
**Type**:: Grass
**Abilities**:: [[SRD-Leaf Guard|Leaf Guard]] / [[SRD-Queenly Majesty|Queenly Majesty]] ([[SRD-Sweet Veil|Sweet Veil]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'9" / 1.2m
**Weight**: 47.2lbs / 21.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Steenee]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Tsareena.md"
flatten moves as T
where file.path = this.file.path
```
