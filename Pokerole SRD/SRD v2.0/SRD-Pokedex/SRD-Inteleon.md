---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-inteleon-BookSprite.png
BoxSprite: SRD-inteleon-BoxSprite.png
DexCategory: Secret Agent Pokemon
DexDescription: Its fingertips can create quick jets of water that travel at incredibly
  high speeds, these jets can even pierce thick metal plates. It usually hunts from
  a high place, shoots, and then glides down to eat its prey.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Drizzile]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Sniper
HomeSprite: SRD-inteleon-HomeSprite.png
Image: inteleon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Snipe Shot|Snipe Shot]]'
- - Starter
  - '[[SRD-Acrobatics|Acrobatics]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Pound|Pound]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Gun|Water Gun]]'
- - Amateur
  - '[[SRD-Bind|Bind]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Tearful Look|Tearful Look]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-U-Turn|U-Turn]]'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - Ace
  - '[[SRD-Soak|Soak]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Pro
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Pro
  - '[[SRD-Hydro Cannon|Hydro Cannon]]'
Number: 818
ShuffleToken: SRD-inteleon-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 45.2
  Pounds: 99.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-inteleon-BookSprite.png|wsmall]]
> ![[SRD-inteleon-HomeSprite.png]]
> ![[SRD-inteleon-BoxSprite.png|htiny]]
> ![[SRD-inteleon-ShuffleToken.png|wsmall]]


*Secret Agent Pokemon*
*Its fingertips can create quick jets of water that travel at incredibly high speeds, these jets can even pierce thick metal plates. It usually hunts from a high place, shoots, and then glides down to eat its prey.*

**DexID**:: 0818
**Name**:: Inteleon
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Sniper|Sniper]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 6'2" / 1.9m
**Weight**: 99.6lbs / 45.2kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Drizzile]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Inteleon.md"
flatten moves as T
where file.path = this.file.path
```
