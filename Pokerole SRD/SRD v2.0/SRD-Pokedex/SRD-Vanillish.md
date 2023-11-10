---
Ability1: Ice Body
Ability2: Snow Cloak
BookSprite: SRD-vanillish-BookSprite.png
BoxSprite: SRD-vanillish-BoxSprite.png
DexCategory: Icy Snow Pokemon
DexDescription: "Snowy mountains are this Pokemon\u2019s habitat. It conceals itself\
  \ from enemy eyes by creating many small ice bundles and hiding around them. It\
  \ may attach itself to the ceiling of ice caves to hide around the ice."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Vanillite]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Vanilluxe]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Weak Armor
HomeSprite: SRD-vanillish-HomeSprite.png
Image: vanillish.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Icicle Spear|Icicle Spear]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - Ace
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Pro
  - '[[SRD-Autotomize|Autotomize]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
Number: 583
ShuffleToken: SRD-vanillish-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 41.0
  Pounds: 90.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vanillish-BookSprite.png|wsmall]]
> ![[SRD-vanillish-HomeSprite.png]]
> ![[SRD-vanillish-BoxSprite.png|htiny]]
> ![[SRD-vanillish-ShuffleToken.png|wsmall]]


*Icy Snow Pokemon*
*Snowy mountains are this Pokemon’s habitat. It conceals itself from enemy eyes by creating many small ice bundles and hiding around them. It may attach itself to the ceiling of ice caves to hide around the ice.*

**DexID**:: 0583
**Name**:: Vanillish
**Type**:: Ice
**Abilities**:: [[SRD-Ice Body|Ice Body]] / [[SRD-Snow Cloak|Snow Cloak]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 90.4lbs / 41.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Vanillite]] | Level  | Medium  |
| To        | [[SRD-Vanilluxe]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Vanillish.md"
flatten moves as T
where file.path = this.file.path
```
