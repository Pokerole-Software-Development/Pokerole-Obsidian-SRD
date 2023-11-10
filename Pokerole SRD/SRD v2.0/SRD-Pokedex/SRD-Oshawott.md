---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-oshawott-BookSprite.png
BoxSprite: SRD-oshawott-BoxSprite.png
DexCategory: Sea Otter Pokemon
DexDescription: It is only seen close to the sea in a few places in the world. Oshawott
  uses the scalchop on its chest as a tool for multiple purposes and as a weapon to
  slash and fight. It is small but brave and daring.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dewott]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Shell Armor
HomeSprite: SRD-oshawott-HomeSprite.png
Image: oshawott.png
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
Number: 501
ShuffleToken: SRD-oshawott-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 5.9
  Pounds: 13.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-oshawott-BookSprite.png|wsmall]]
> ![[SRD-oshawott-HomeSprite.png]]
> ![[SRD-oshawott-BoxSprite.png|htiny]]
> ![[SRD-oshawott-ShuffleToken.png|wsmall]]


*Sea Otter Pokemon*
*It is only seen close to the sea in a few places in the world. Oshawott uses the scalchop on its chest as a tool for multiple purposes and as a weapon to slash and fight. It is small but brave and daring.*

**DexID**:: 0501
**Name**:: Oshawott
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Shell Armor|Shell Armor]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 13.0lbs / 5.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Dewott]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Oshawott.md"
flatten moves as T
where file.path = this.file.path
```
