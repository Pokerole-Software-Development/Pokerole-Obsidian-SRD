---
Ability1: Suction Cups
Ability2: ''
BookSprite: SRD-lileep-BookSprite.png
BoxSprite: SRD-lileep-BoxSprite.png
DexCategory: Sea Lily Pokemon
DexDescription: Over 100 million years ago, Lileep used to attach themselves to rocks
  at the bottom of the sea. A catastrophe led them all to extinction. A few fossils
  were found and some were revived by scientists.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Cradily]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Storm Drain
HomeSprite: SRD-lileep-HomeSprite.png
Image: lileep.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Acid|Acid]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Energy Ball|Energy Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Spit Up|Spit Up]]'
- - Ace
  - '[[SRD-Stockpile|Stockpile]]'
- - Ace
  - '[[SRD-Swallow|Swallow]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Earth Power|Earth Power]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
Number: 345
ShuffleToken: SRD-lileep-ShuffleToken.png
Type1: Rock
Type2: Grass
Weight:
  Kilograms: 23.8
  Pounds: 52.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lileep-BookSprite.png|wsmall]]
> ![[SRD-lileep-HomeSprite.png]]
> ![[SRD-lileep-BoxSprite.png|htiny]]
> ![[SRD-lileep-ShuffleToken.png|wsmall]]


*Sea Lily Pokemon*
*Over 100 million years ago, Lileep used to attach themselves to rocks at the bottom of the sea. A catastrophe led them all to extinction. A few fossils were found and some were revived by scientists.*

**DexID**:: 0345
**Name**:: Lileep
**Type**:: Rock / Grass
**Abilities**:: [[SRD-Suction Cups|Suction Cups]] ([[SRD-Storm Drain|Storm Drain]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 52.5lbs / 23.8kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Cradily]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Lileep.md"
flatten moves as T
where file.path = this.file.path
```
