---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-croconaw-BookSprite.png
BoxSprite: SRD-croconaw-BoxSprite.png
DexCategory: Big Jaw Pokemon
DexDescription: "This Pokemon is really tenacious. Once it bites something it won\u2019\
  t let go until it tears it down - even if its trainer is ordering to let go. If\
  \ it loses any of it\u2019s fangs, they\u2019ll regrow in a few days. It\u2019s\
  \ a very wild Pokemon."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Totodile]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Feraligatr]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Sheer Force
HomeSprite: SRD-croconaw-HomeSprite.png
Image: croconaw.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
Number: 159
ShuffleToken: SRD-croconaw-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 25.0
  Pounds: 55.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-croconaw-BookSprite.png|wsmall]]
> ![[SRD-croconaw-HomeSprite.png]]
> ![[SRD-croconaw-BoxSprite.png|htiny]]
> ![[SRD-croconaw-ShuffleToken.png|wsmall]]


*Big Jaw Pokemon*
*This Pokemon is really tenacious. Once it bites something it won’t let go until it tears it down - even if its trainer is ordering to let go. If it loses any of it’s fangs, they’ll regrow in a few days. It’s a very wild Pokemon.*

**DexID**:: 0159
**Name**:: Croconaw
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 55.1lbs / 25.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Totodile]]   | Level  | Medium  |
| To        | [[SRD-Feraligatr]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Croconaw.md"
flatten moves as T
where file.path = this.file.path
```
