---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-grotle-BookSprite.png
BoxSprite: SRD-grotle-BoxSprite.png
DexCategory: Grove Pokemon
DexDescription: "Other Pokemon harass Grotle when the bushes on its back have berries\
  \ or fruit. It patiently waits for others to finish eating before moving. It loves\
  \ clear water and it\u2019s good at finding cool ponds and springs."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Turtwig]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Torterra]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Shell Armor
HomeSprite: SRD-grotle-HomeSprite.png
Image: grotle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Withdraw|Withdraw]]'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
- - Pro
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
Number: 388
ShuffleToken: SRD-grotle-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 97.0
  Pounds: 213.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-grotle-BookSprite.png|wsmall]]
> ![[SRD-grotle-HomeSprite.png]]
> ![[SRD-grotle-BoxSprite.png|htiny]]
> ![[SRD-grotle-ShuffleToken.png|wsmall]]


*Grove Pokemon*
*Other Pokemon harass Grotle when the bushes on its back have berries or fruit. It patiently waits for others to finish eating before moving. It loves clear water and it’s good at finding cool ponds and springs.*

**DexID**:: 0388
**Name**:: Grotle
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Shell Armor|Shell Armor]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 213.8lbs / 97.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Turtwig]]  | Level  | Medium  |
| To        | [[SRD-Torterra]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Grotle.md"
flatten moves as T
where file.path = this.file.path
```
