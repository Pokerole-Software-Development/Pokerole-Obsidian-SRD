---
Ability1: Static
Ability2: ''
BookSprite: SRD-mareep-BookSprite.png
BoxSprite: SRD-mareep-BoxSprite.png
DexCategory: Wool Pokemon
DexDescription: Its fluffy coat of wool builds a static charge, the more static electricity,
  the more brightly the lightbulb at the tip of its tail glows. Farmers shed their
  wool by the summer but it grows back quickly.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Flaaffy]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Plus
HomeSprite: SRD-mareep-HomeSprite.png
Image: mareep.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Cotton Spore|Cotton Spore]]'
- - Amateur
  - '[[SRD-Charge|Charge]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Thunder|Thunder]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
Number: 179
ShuffleToken: SRD-mareep-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 7.8
  Pounds: 17.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mareep-BookSprite.png|wsmall]]
> ![[SRD-mareep-HomeSprite.png]]
> ![[SRD-mareep-BoxSprite.png|htiny]]
> ![[SRD-mareep-ShuffleToken.png|wsmall]]


*Wool Pokemon*
*Its fluffy coat of wool builds a static charge, the more static electricity, the more brightly the lightbulb at the tip of its tail glows. Farmers shed their wool by the summer but it grows back quickly.*

**DexID**:: 0179
**Name**:: Mareep
**Type**:: Electric
**Abilities**:: [[SRD-Static|Static]] ([[SRD-Plus|Plus]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 17.2lbs / 7.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Flaaffy]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mareep.md"
flatten moves as T
where file.path = this.file.path
```
