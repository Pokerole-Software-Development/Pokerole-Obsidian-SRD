---
Ability1: Keen Eye
Ability2: Stall
BookSprite: SRD-sableye-BookSprite.png
BoxSprite: SRD-sableye-BoxSprite.png
DexCategory: Darkness Pokemon
DexDescription: Feared for stealing the souls of men with their sinister eyes glowing
  in the dark. They lurk deep inside caves, eating rocks, gemstones and crystals.
  Luckily, Sableyes are rarely seen. They love jewels and treasure.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Sablenite
  Kind: Mega
  Pokemon: '[[SRD-Sableye (Mega Form)]]'
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Prankster
HomeSprite: SRD-sableye-HomeSprite.png
Image: sableye.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Mean Look|Mean Look]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Foresight|Foresight]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Astonish|Astonish]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Fake Out|Fake Out]]'
- - Amateur
  - '[[SRD-Detect|Detect]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Punishment|Punishment]]'
- - Ace
  - '[[SRD-Foul Play|Foul Play]]'
- - Ace
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Pro
  - '[[SRD-Moonlight|Moonlight]]'
Number: 302
ShuffleToken: SRD-sableye-ShuffleToken.png
Type1: Dark
Type2: Ghost
Weight:
  Kilograms: 11.0
  Pounds: 24.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sableye-BookSprite.png|wsmall]]
> ![[SRD-sableye-HomeSprite.png]]
> ![[SRD-sableye-BoxSprite.png|htiny]]
> ![[SRD-sableye-ShuffleToken.png|wsmall]]


*Darkness Pokemon*
*Feared for stealing the souls of men with their sinister eyes glowing in the dark. They lurk deep inside caves, eating rocks, gemstones and crystals. Luckily, Sableyes are rarely seen. They love jewels and treasure.*

**DexID**:: 0302
**Name**:: Sableye
**Type**:: Dark / Ghost
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Stall|Stall]] ([[SRD-Prankster|Prankster]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 24.3lbs / 11.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                     | Kind   | Item      |
|:----------|:----------------------------|:-------|:----------|
| To        | [[SRD-Sableye (Mega Form)]] | Mega   | Sablenite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Sableye.md"
flatten moves as T
where file.path = this.file.path
```
