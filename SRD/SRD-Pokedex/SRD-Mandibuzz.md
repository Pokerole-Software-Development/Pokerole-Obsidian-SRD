---
Ability1: Big Pecks
Ability2: Overcoat
BookSprite: SRD-mandibuzz-BookSprite.png
BoxSprite: SRD-mandibuzz-BoxSprite.png
DexCategory: Bone Vulture Pokemon
DexDescription: They fly in circles around the sky when they spot prey. They carry
  the carcass back to their nest with ease. They like to look beautiful and create
  ornaments and jewelry using bone pieces.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Vullaby]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Weak Armor
HomeSprite: SRD-mandibuzz-HomeSprite.png
Image: mandibuzz.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Gust|Gust]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Beginner
  - '[[SRD-Pluck|Pluck]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Flatter|Flatter]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Punishment|Punishment]]'
- - Amateur
  - '[[SRD-Defog|Defog]]'
- - Amateur
  - '[[SRD-Tailwind|Tailwind]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Amateur
  - '[[SRD-Bone Rush|Bone Rush]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mirror Move|Mirror Move]]'
- - Ace
  - '[[SRD-Embargo|Embargo]]'
- - Ace
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Scary Face|Scary Face]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
Number: 630
ShuffleToken: SRD-mandibuzz-ShuffleToken.png
Type1: Dark
Type2: Flying
Weight:
  Kilograms: 39.5
  Pounds: 87.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mandibuzz-BookSprite.png|wsmall]]
> ![[SRD-mandibuzz-HomeSprite.png]]
> ![[SRD-mandibuzz-BoxSprite.png|htiny]]
> ![[SRD-mandibuzz-ShuffleToken.png|wsmall]]


*Bone Vulture Pokemon*
*They fly in circles around the sky when they spot prey. They carry the carcass back to their nest with ease. They like to look beautiful and create ornaments and jewelry using bone pieces.*

**DexID**:: 0630
**Name**:: Mandibuzz
**Type**:: Dark / Flying
**Abilities**:: [[SRD-Big Pecks|Big Pecks]] / [[SRD-Overcoat|Overcoat]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'9" / 1.2m
**Weight**: 87.1lbs / 39.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Vullaby]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Mandibuzz.md"
flatten moves as T
where file.path = this.file.path
```
