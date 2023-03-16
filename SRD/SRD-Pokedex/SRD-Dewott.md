---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-dewott-BookSprite.png
BoxSprite: SRD-dewott-BoxSprite.png
DexCategory: Discipline Pokemon
DexDescription: "It isolates itself from others and trains every day to perform a\
  \ double scalchop slash technique. This Pokemon takes itself very seriously and\
  \ won\u2019t back down from any challenge."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Oshawott]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Samurott]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Shell Armor
HomeSprite: SRD-dewott-HomeSprite.png
Image: dewott.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Razor Shell|Razor Shell]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Retaliate|Retaliate]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
- - Pro
  - '[[SRD-Air Slash|Air Slash]]'
- - Pro
  - '[[SRD-Detect|Detect]]'
Number: 502
ShuffleToken: SRD-dewott-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 24.5
  Pounds: 54.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dewott-BookSprite.png|wsmall]]
> ![[SRD-dewott-HomeSprite.png]]
> ![[SRD-dewott-BoxSprite.png|htiny]]
> ![[SRD-dewott-ShuffleToken.png|wsmall]]


*Discipline Pokemon*
*It isolates itself from others and trains every day to perform a double scalchop slash technique. This Pokemon takes itself very seriously and won’t back down from any challenge.*

**DexID**:: 0502
**Name**:: Dewott
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Shell Armor|Shell Armor]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 54.0lbs / 24.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Oshawott]] | Level  | Medium  |
| To        | [[SRD-Samurott]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Dewott.md"
flatten moves as T
where file.path = this.file.path
```
