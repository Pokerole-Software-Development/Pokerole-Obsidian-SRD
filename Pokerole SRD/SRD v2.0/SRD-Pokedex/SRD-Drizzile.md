---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-drizzile-BookSprite.png
BoxSprite: SRD-drizzile-BoxSprite.png
DexCategory: Water Lizard Pokemon
DexDescription: Its demeanor changes drastically from shy to aloof and lazy. It can
  create water balloons with the moisture secreted from its paws. It is incredibly
  intelligent and is known to lay traps for others in the wild.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Sobble]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Inteleon]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Sniper
HomeSprite: SRD-drizzile-HomeSprite.png
Image: drizzile.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Tearful Look|Tearful Look]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-U-Turn|U-Turn]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - Ace
  - '[[SRD-Soak|Soak]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Double Team|Double Team]]'
- - Pro
  - '[[SRD-Haze|Haze]]'
- - Pro
  - '[[SRD-Aqua Jet|Aqua Jet]]'
Number: 817
ShuffleToken: SRD-drizzile-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 11.5
  Pounds: 25.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-drizzile-BookSprite.png|wsmall]]
> ![[SRD-drizzile-HomeSprite.png]]
> ![[SRD-drizzile-BoxSprite.png|htiny]]
> ![[SRD-drizzile-ShuffleToken.png|wsmall]]


*Water Lizard Pokemon*
*Its demeanor changes drastically from shy to aloof and lazy. It can create water balloons with the moisture secreted from its paws. It is incredibly intelligent and is known to lay traps for others in the wild.*

**DexID**:: 0817
**Name**:: Drizzile
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Sniper|Sniper]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 25.4lbs / 11.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Sobble]]   | Level  | Medium  |
| To        | [[SRD-Inteleon]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Drizzile.md"
flatten moves as T
where file.path = this.file.path
```
