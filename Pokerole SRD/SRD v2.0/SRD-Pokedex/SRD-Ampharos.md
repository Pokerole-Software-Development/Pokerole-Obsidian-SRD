---
Ability1: Static
Ability2: ''
BookSprite: SRD-ampharos-BookSprite.png
BoxSprite: SRD-ampharos-BoxSprite.png
DexCategory: Light Pokemon
DexDescription: "It\u2019s not common to see it in the wild. The tip of its tail shines\
  \ brightly and in the old days, people sent light signals with the help of this\
  \ Pokemon. It has a good disposition towards people in general."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Flaaffy]]'
  Speed: Medium
- Evolves: To
  Item: Ampharosite
  Kind: Mega
  Pokemon: '[[SRD-Ampharos (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Plus
HomeSprite: SRD-ampharos-HomeSprite.png
Image: ampharos.png
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
  - '[[SRD-Magnetic Flux|Magnetic Flux]]'
- - Amateur
  - '[[SRD-Ion Deluge|Ion Deluge]]'
- - Amateur
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
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
  - '[[SRD-Thunder Punch|Thunder Punch]]'
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
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 181
ShuffleToken: SRD-ampharos-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 61.5
  Pounds: 135.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-ampharos-BookSprite.png|wsmall]]
> ![[SRD-ampharos-HomeSprite.png]]
> ![[SRD-ampharos-BoxSprite.png|htiny]]
> ![[SRD-ampharos-ShuffleToken.png|wsmall]]


*Light Pokemon*
*It’s not common to see it in the wild. The tip of its tail shines brightly and in the old days, people sent light signals with the help of this Pokemon. It has a good disposition towards people in general.*

**DexID**:: 0181
**Name**:: Ampharos
**Type**:: Electric
**Abilities**:: [[SRD-Static|Static]] ([[SRD-Plus|Plus]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 135.6lbs / 61.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                      | Kind   | Speed   | Item        |
|:----------|:-----------------------------|:-------|:--------|:------------|
| From      | [[SRD-Flaaffy]]              | Level  | Medium  |             |
| To        | [[SRD-Ampharos (Mega Form)]] | Mega   |         | Ampharosite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Ampharos.md"
flatten moves as T
where file.path = this.file.path
```
