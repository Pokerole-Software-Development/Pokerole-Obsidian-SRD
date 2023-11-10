---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-sobble-BookSprite.png
BoxSprite: SRD-sobble-BoxSprite.png
DexCategory: Water Lizard Pokemon
DexDescription: This shy Pokemon does not like to attract too much attention. It hides
  in shallow pools of water.. When it feels threatened it cries and its tears pack
  release a chemical that will make its foes cry too.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Drizzile]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Sniper
HomeSprite: SRD-sobble-HomeSprite.png
Image: sobble.png
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
  - '[[SRD-Mist|Mist]]'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
Number: 816
ShuffleToken: SRD-sobble-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 4.0
  Pounds: 8.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sobble-BookSprite.png|wsmall]]
> ![[SRD-sobble-HomeSprite.png]]
> ![[SRD-sobble-BoxSprite.png|htiny]]
> ![[SRD-sobble-ShuffleToken.png|wsmall]]


*Water Lizard Pokemon*
*This shy Pokemon does not like to attract too much attention. It hides in shallow pools of water.. When it feels threatened it cries and its tears pack release a chemical that will make its foes cry too.*

**DexID**:: 0816
**Name**:: Sobble
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Sniper|Sniper]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 8.8lbs / 4.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Drizzile]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sobble.md"
flatten moves as T
where file.path = this.file.path
```
