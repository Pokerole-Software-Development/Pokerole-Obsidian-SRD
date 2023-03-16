---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-samurott-BookSprite.png
BoxSprite: SRD-samurott-BoxSprite.png
DexCategory: Formidable Pokemon
DexDescription: "It uses the horn on it\u2019s head and both scimitars attached to\
  \ it\u2019s front legs as weapons. In the late spring and fall, they gather on cold\
  \ beaches and fight each other. The winner lets out an intimidating roar."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Dewott]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Shell Armor
HomeSprite: SRD-samurott-HomeSprite.png
Image: samurott.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Encore|Encore]]'
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
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Megahorn|Megahorn]]'
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
  - '[[SRD-Hydro Cannon|Hydro Cannon]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Smart Strike|Smart Strike]]'
Number: 503
ShuffleToken: SRD-samurott-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 94.6
  Pounds: 208.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-samurott-BookSprite.png|wsmall]]
> ![[SRD-samurott-HomeSprite.png]]
> ![[SRD-samurott-BoxSprite.png|htiny]]
> ![[SRD-samurott-ShuffleToken.png|wsmall]]


*Formidable Pokemon*
*It uses the horn on it’s head and both scimitars attached to it’s front legs as weapons. In the late spring and fall, they gather on cold beaches and fight each other. The winner lets out an intimidating roar.*

**DexID**:: 0503
**Name**:: Samurott
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Shell Armor|Shell Armor]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 208.6lbs / 94.6kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Dewott]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Samurott.md"
flatten moves as T
where file.path = this.file.path
```
