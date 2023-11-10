---
Ability1: Snow Warning
Ability2: ''
BookSprite: SRD-snover-BookSprite.png
BoxSprite: SRD-snover-BoxSprite.png
DexCategory: Frosted Tree Pokemon
DexDescription: "During cold seasons, it migrates to the mountain\u2019s lower reaches\
  \ and returns to the summit in the spring. They are rarely in contact with humans\
  \ but are sought for the frozen berries they grow."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Abomasnow]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Soundproof
HomeSprite: SRD-snover-HomeSprite.png
Image: snover.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Grass Whistle|Grass Whistle]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Growth|Growth]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
Number: 459
ShuffleToken: SRD-snover-ShuffleToken.png
Type1: Grass
Type2: Ice
Weight:
  Kilograms: 50.5
  Pounds: 111.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-snover-BookSprite.png|wsmall]]
> ![[SRD-snover-HomeSprite.png]]
> ![[SRD-snover-BoxSprite.png|htiny]]
> ![[SRD-snover-ShuffleToken.png|wsmall]]


*Frosted Tree Pokemon*
*During cold seasons, it migrates to the mountain’s lower reaches and returns to the summit in the spring. They are rarely in contact with humans but are sought for the frozen berries they grow.*

**DexID**:: 0459
**Name**:: Snover
**Type**:: Grass / Ice
**Abilities**:: [[SRD-Snow Warning|Snow Warning]] ([[SRD-Soundproof|Soundproof]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 111.3lbs / 50.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Abomasnow]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Snover.md"
flatten moves as T
where file.path = this.file.path
```
