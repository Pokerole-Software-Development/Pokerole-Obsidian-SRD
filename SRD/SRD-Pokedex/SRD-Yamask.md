---
Ability1: Mummy
Ability2: ''
BookSprite: SRD-yamask-BookSprite.png
BoxSprite: SRD-yamask-BoxSprite.png
DexCategory: Spirit Pokemon
DexDescription: This Pokemon arose from the spirit of a human or a Pokemon that died
  in the past and was buried with special ceremonies. Each one carries a mask that
  looks like the face it had in life. A sad Pokemon that weeps often.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Cofagrigus]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: ''
HomeSprite: SRD-yamask-HomeSprite.png
Image: yamask.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - Beginner
  - '[[SRD-Haze|Haze]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Night Shade|Night Shade]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Power Split|Power Split]]'
- - Amateur
  - '[[SRD-Guard Split|Guard Split]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Mean Look|Mean Look]]'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Role Play|Role Play]]'
Number: 562
ShuffleToken: SRD-yamask-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 1.5
  Pounds: 3.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-yamask-BookSprite.png|wsmall]]
> ![[SRD-yamask-HomeSprite.png]]
> ![[SRD-yamask-BoxSprite.png|htiny]]
> ![[SRD-yamask-ShuffleToken.png|wsmall]]


*Spirit Pokemon*
*This Pokemon arose from the spirit of a human or a Pokemon that died in the past and was buried with special ceremonies. Each one carries a mask that looks like the face it had in life. A sad Pokemon that weeps often.*

**DexID**:: 0562
**Name**:: Yamask
**Type**:: Ghost
**Abilities**:: [[SRD-Mummy|Mummy]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 3.3lbs / 1.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Cofagrigus]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Yamask.md"
flatten moves as T
where file.path = this.file.path
```
