---
Ability1: Static
Ability2: ''
BookSprite: SRD-electabuzz-BookSprite.png
BoxSprite: SRD-electabuzz-BoxSprite.png
DexCategory: Electric Pokemon
DexDescription: "A violent Pokemon. It searches for spots where it can feed on electricity\
  \ and has been seen absorbing lightning from the sky. It\u2019s competitive and\
  \ aggressive with others."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Elekid]]'
  Speed: Medium
- Evolves: To
  Item: Electirizer
  Kind: Trade
  Pokemon: '[[SRD-Electivire]]'
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Vital Spirit
HomeSprite: SRD-electabuzz-HomeSprite.png
Image: electabuzz.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Beginner
  - '[[SRD-Low Kick|Low Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Screech|Screech]]'
- - Ace
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Ace
  - '[[SRD-Thunder|Thunder]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Meditate|Meditate]]'
Number: 125
ShuffleToken: SRD-electabuzz-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 30.0
  Pounds: 66.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-electabuzz-BookSprite.png|wsmall]]
> ![[SRD-electabuzz-HomeSprite.png]]
> ![[SRD-electabuzz-BoxSprite.png|htiny]]
> ![[SRD-electabuzz-ShuffleToken.png|wsmall]]


*Electric Pokemon*
*A violent Pokemon. It searches for spots where it can feed on electricity and has been seen absorbing lightning from the sky. It’s competitive and aggressive with others.*

**DexID**:: 0125
**Name**:: Electabuzz
**Type**:: Electric
**Abilities**:: [[SRD-Static|Static]] ([[SRD-Vital Spirit|Vital Spirit]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 66.1lbs / 30.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   | Item        |
|:----------|:-------------------|:-------|:--------|:------------|
| From      | [[SRD-Elekid]]     | Level  | Medium  |             |
| To        | [[SRD-Electivire]] | Trade  |         | Electirizer |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Electabuzz.md"
flatten moves as T
where file.path = this.file.path
```
