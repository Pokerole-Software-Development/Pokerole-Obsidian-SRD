---
Ability1: Chlorophyll
Ability2: Early Bird
BookSprite: SRD-nuzleaf-BookSprite.png
BoxSprite: SRD-nuzleaf-BoxSprite.png
DexCategory: Wily Pokemon
DexDescription: "They live inside holes on big trees. Their leaves are played like\
  \ flutes to strike fear and discomfort in lost people\u2019s hearts. They like to\
  \ go out and startle people. Their noses are really sensitive and frail."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Seedot]]'
  Speed: Medium
- Evolves: To
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Shiftry]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Pickpocket
HomeSprite: SRD-nuzleaf-HomeSprite.png
Image: nuzleaf.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Nature Power|Nature Power]]'
- - Amateur
  - '[[SRD-Fake Out|Fake Out]]'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Ace
  - '[[SRD-Swagger|Swagger]]'
- - Ace
  - '[[SRD-Extrasensory|Extrasensory]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Pro
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
Number: 274
ShuffleToken: SRD-nuzleaf-ShuffleToken.png
Type1: Grass
Type2: Dark
Weight:
  Kilograms: 28.0
  Pounds: 61.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-nuzleaf-BookSprite.png|wsmall]]
> ![[SRD-nuzleaf-HomeSprite.png]]
> ![[SRD-nuzleaf-BoxSprite.png|htiny]]
> ![[SRD-nuzleaf-ShuffleToken.png|wsmall]]


*Wily Pokemon*
*They live inside holes on big trees. Their leaves are played like flutes to strike fear and discomfort in lost people’s hearts. They like to go out and startle people. Their noses are really sensitive and frail.*

**DexID**:: 0274
**Name**:: Nuzleaf
**Type**:: Grass / Dark
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Early Bird|Early Bird]] ([[SRD-Pickpocket|Pickpocket]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 3'3" / 1.0m
**Weight**: 61.7lbs / 28.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   | Item       |
|:----------|:----------------|:-------|:--------|:-----------|
| From      | [[SRD-Seedot]]  | Level  | Medium  |            |
| To        | [[SRD-Shiftry]] | Stone  |         | Leaf Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Nuzleaf.md"
flatten moves as T
where file.path = this.file.path
```
