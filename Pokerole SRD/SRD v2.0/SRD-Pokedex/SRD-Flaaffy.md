---
Ability1: Static
Ability2: ''
BookSprite: SRD-flaaffy-BookSprite.png
BoxSprite: SRD-flaaffy-BoxSprite.png
DexCategory: Wool Pokemon
DexDescription: Its wool quality changes so that it can generate a higher amount of
  static electricity with a smaller amount of wool. The bare and slick parts of its
  hide are shielded with small electric impulses.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Mareep]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Ampharos]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Plus
HomeSprite: SRD-flaaffy-HomeSprite.png
Image: flaaffy.png
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
Number: 180
ShuffleToken: SRD-flaaffy-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 13.3
  Pounds: 29.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-flaaffy-BookSprite.png|wsmall]]
> ![[SRD-flaaffy-HomeSprite.png]]
> ![[SRD-flaaffy-BoxSprite.png|htiny]]
> ![[SRD-flaaffy-ShuffleToken.png|wsmall]]


*Wool Pokemon*
*Its wool quality changes so that it can generate a higher amount of static electricity with a smaller amount of wool. The bare and slick parts of its hide are shielded with small electric impulses.*

**DexID**:: 0180
**Name**:: Flaaffy
**Type**:: Electric
**Abilities**:: [[SRD-Static|Static]] ([[SRD-Plus|Plus]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 29.3lbs / 13.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Mareep]]   | Level  | Medium  |
| To        | [[SRD-Ampharos]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Flaaffy.md"
flatten moves as T
where file.path = this.file.path
```
