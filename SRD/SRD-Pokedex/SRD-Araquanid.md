---
Ability1: Water Bubble
Ability2: ''
BookSprite: SRD-araquanid-BookSprite.png
BoxSprite: SRD-araquanid-BoxSprite.png
DexCategory: Water Bubble Pokemon
DexDescription: "It\u2019s debated whether this is a caring or cruel Pokemon. It looks\
  \ around for any vulnerable or weak pokemon, tenderly carries them and deposits\
  \ them into its water bubble where they end up drowning."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Dewpider]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Water Absorb
HomeSprite: SRD-araquanid-HomeSprite.png
Image: araquanid.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Infestation|Infestation]]'
- - Beginner
  - '[[SRD-Spider Web|Spider Web]]'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Soak|Soak]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Leech Life|Leech Life]]'
- - Amateur
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Amateur
  - '[[SRD-Lunge|Lunge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Power Split|Power Split]]'
- - Pro
  - '[[SRD-Attract|Attract]]'
- - Pro
  - '[[SRD-Scald|Scald]]'
Number: 752
ShuffleToken: SRD-araquanid-ShuffleToken.png
Type1: Water
Type2: Bug
Weight:
  Kilograms: 82.0
  Pounds: 180.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-araquanid-BookSprite.png|wsmall]]
> ![[SRD-araquanid-HomeSprite.png]]
> ![[SRD-araquanid-BoxSprite.png|htiny]]
> ![[SRD-araquanid-ShuffleToken.png|wsmall]]


*Water Bubble Pokemon*
*It’s debated whether this is a caring or cruel Pokemon. It looks around for any vulnerable or weak pokemon, tenderly carries them and deposits them into its water bubble where they end up drowning.*

**DexID**:: 0752
**Name**:: Araquanid
**Type**:: Water / Bug
**Abilities**:: [[SRD-Water Bubble|Water Bubble]] ([[SRD-Water Absorb|Water Absorb]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 5'9" / 1.8m
**Weight**: 180.8lbs / 82.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Dewpider]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Araquanid.md"
flatten moves as T
where file.path = this.file.path
```
