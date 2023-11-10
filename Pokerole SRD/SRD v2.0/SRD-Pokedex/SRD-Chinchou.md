---
Ability1: Volt Absorb
Ability2: Illuminate
BookSprite: SRD-chinchou-BookSprite.png
BoxSprite: SRD-chinchou-BoxSprite.png
DexCategory: Angler Pokemon
DexDescription: In the dark ocean floor, its only mean of communication is to constantly
  flash its lights. It is a clumsy but friendly Pokemon. Its antennae can be used
  to power up small electric appliances.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Lanturn]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Water Absorb
HomeSprite: SRD-chinchou-HomeSprite.png
Image: chinchou.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[SRD-Flail|Flail]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Ion Deluge|Ion Deluge]]'
- - Ace
  - '[[SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Soak|Soak]]'
- - Pro
  - '[[SRD-Psybeam|Psybeam]]'
Number: 170
ShuffleToken: SRD-chinchou-ShuffleToken.png
Type1: Water
Type2: Electric
Weight:
  Kilograms: 12.0
  Pounds: 26.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-chinchou-BookSprite.png|wsmall]]
> ![[SRD-chinchou-HomeSprite.png]]
> ![[SRD-chinchou-BoxSprite.png|htiny]]
> ![[SRD-chinchou-ShuffleToken.png|wsmall]]


*Angler Pokemon*
*In the dark ocean floor, its only mean of communication is to constantly flash its lights. It is a clumsy but friendly Pokemon. Its antennae can be used to power up small electric appliances.*

**DexID**:: 0170
**Name**:: Chinchou
**Type**:: Water / Electric
**Abilities**:: [[SRD-Volt Absorb|Volt Absorb]] / [[SRD-Illuminate|Illuminate]] ([[SRD-Water Absorb|Water Absorb]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 26.5lbs / 12.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Lanturn]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Chinchou.md"
flatten moves as T
where file.path = this.file.path
```
