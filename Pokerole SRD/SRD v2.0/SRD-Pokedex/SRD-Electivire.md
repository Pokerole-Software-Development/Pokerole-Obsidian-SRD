---
Ability1: Motor Drive
Ability2: ''
BookSprite: SRD-electivire-BookSprite.png
BoxSprite: SRD-electivire-BoxSprite.png
DexCategory: Thunderbolt Pokemon
DexDescription: This Pokemon is reckless and has a short temper. As its electric charge
  amplifies, blue sparks begin to crackle between its horns. It has registered charge
  levels of over 20,000 Volts.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Electirizer
  Kind: Trade
  Pokemon: '[[SRD-Electabuzz]]'
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Vital Spirit
HomeSprite: SRD-electivire-HomeSprite.png
Image: electivire.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Ion Deluge|Ion Deluge]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - Beginner
  - '[[SRD-Low Kick|Low Kick]]'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Thunderbolt|Thunderbolt]]'
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
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Screech|Screech]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Thunder|Thunder]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
Number: 466
ShuffleToken: SRD-electivire-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 138.6
  Pounds: 305.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-electivire-BookSprite.png|wsmall]]
> ![[SRD-electivire-HomeSprite.png]]
> ![[SRD-electivire-BoxSprite.png|htiny]]
> ![[SRD-electivire-ShuffleToken.png|wsmall]]


*Thunderbolt Pokemon*
*This Pokemon is reckless and has a short temper. As its electric charge amplifies, blue sparks begin to crackle between its horns. It has registered charge levels of over 20,000 Volts.*

**DexID**:: 0466
**Name**:: Electivire
**Type**:: Electric
**Abilities**:: [[SRD-Motor Drive|Motor Drive]] ([[SRD-Vital Spirit|Vital Spirit]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 305.6lbs / 138.6kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon            | Kind   | Item        |
|:----------|:-------------------|:-------|:------------|
| From      | [[SRD-Electabuzz]] | Trade  | Electirizer |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Electivire.md"
flatten moves as T
where file.path = this.file.path
```
