---
Ability1: Volt Absorb
Ability2: Illuminate
BookSprite: SRD-lanturn-BookSprite.png
BoxSprite: SRD-lanturn-BoxSprite.png
DexCategory: Light Pokemon
DexDescription: "It is known for its soft light glow. They are not aggressive Pokemon.\
  \ If you look into the dark sea at night you can sometimes see this Pokemon\u2019\
  s light rising from the depths, making the sea look like a starry night."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Chinchou]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Water Absorb
HomeSprite: SRD-lanturn-HomeSprite.png
Image: lanturn.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Flail|Flail]]'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Eerie Impulse|Eerie Impulse]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Amateur
  - '[[SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Ion Deluge|Ion Deluge]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Soak|Soak]]'
- - Pro
  - '[[SRD-Psybeam|Psybeam]]'
Number: 171
ShuffleToken: SRD-lanturn-ShuffleToken.png
Type1: Water
Type2: Electric
Weight:
  Kilograms: 22.5
  Pounds: 49.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lanturn-BookSprite.png|wsmall]]
> ![[SRD-lanturn-HomeSprite.png]]
> ![[SRD-lanturn-BoxSprite.png|htiny]]
> ![[SRD-lanturn-ShuffleToken.png|wsmall]]


*Light Pokemon*
*It is known for its soft light glow. They are not aggressive Pokemon. If you look into the dark sea at night you can sometimes see this Pokemon’s light rising from the depths, making the sea look like a starry night.*

**DexID**:: 0171
**Name**:: Lanturn
**Type**:: Water / Electric
**Abilities**:: [[SRD-Volt Absorb|Volt Absorb]] / [[SRD-Illuminate|Illuminate]] ([[SRD-Water Absorb|Water Absorb]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 49.6lbs / 22.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Chinchou]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Lanturn.md"
flatten moves as T
where file.path = this.file.path
```
