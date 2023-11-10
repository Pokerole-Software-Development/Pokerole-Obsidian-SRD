---
Ability1: Illuminate
Ability2: Natural Cure
BookSprite: SRD-staryu-BookSprite.png
BoxSprite: SRD-staryu-BoxSprite.png
DexCategory: Starshape Pokemon
DexDescription: They come out to the shore in great numbers when the sky is full with
  stars. The core at its center glows to communicate with others. If a part of its
  body is injured it can regrow it in a few days.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Water Stone
  Kind: Stone
  Pokemon: '[[SRD-Starmie]]'
GenderType: N
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Analytic
HomeSprite: SRD-staryu-HomeSprite.png
Image: staryu.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Beginner
  - '[[SRD-Recover|Recover]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Camouflage|Camouflage]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Reflect Type|Reflect Type]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
Number: 120
ShuffleToken: SRD-staryu-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 34.5
  Pounds: 76.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-staryu-BookSprite.png|wsmall]]
> ![[SRD-staryu-HomeSprite.png]]
> ![[SRD-staryu-BoxSprite.png|htiny]]
> ![[SRD-staryu-ShuffleToken.png|wsmall]]


*Starshape Pokemon*
*They come out to the shore in great numbers when the sky is full with stars. The core at its center glows to communicate with others. If a part of its body is injured it can regrow it in a few days.*

**DexID**:: 0120
**Name**:: Staryu
**Type**:: Water
**Abilities**:: [[SRD-Illuminate|Illuminate]] / [[SRD-Natural Cure|Natural Cure]] ([[SRD-Analytic|Analytic]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 76.1lbs / 34.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Item        |
|:----------|:----------------|:-------|:------------|
| To        | [[SRD-Starmie]] | Stone  | Water Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Staryu.md"
flatten moves as T
where file.path = this.file.path
```
