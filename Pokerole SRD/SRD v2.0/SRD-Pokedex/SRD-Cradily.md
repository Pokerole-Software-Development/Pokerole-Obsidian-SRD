---
Ability1: Suction Cups
Ability2: ''
BookSprite: SRD-cradily-BookSprite.png
BoxSprite: SRD-cradily-BoxSprite.png
DexCategory: Barnacle Pokemon
DexDescription: Cradily moves slowly at the bottom of the sea. It uses its body as
  an anchor and its tentacles as arms to catch prey. Their foes are melted with a
  potent acid before being consumed.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Lileep]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Storm Drain
HomeSprite: SRD-cradily-HomeSprite.png
Image: cradily.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Acid|Acid]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - Amateur
  - '[[SRD-Wring Out|Wring Out]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Amnesia|Amnesia]]'
- - Ace
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Ace
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Ace
  - '[[SRD-Energy Ball|Energy Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Worry Seed|Worry Seed]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
Number: 346
ShuffleToken: SRD-cradily-ShuffleToken.png
Type1: Rock
Type2: Grass
Weight:
  Kilograms: 60.4
  Pounds: 133.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cradily-BookSprite.png|wsmall]]
> ![[SRD-cradily-HomeSprite.png]]
> ![[SRD-cradily-BoxSprite.png|htiny]]
> ![[SRD-cradily-ShuffleToken.png|wsmall]]


*Barnacle Pokemon*
*Cradily moves slowly at the bottom of the sea. It uses its body as an anchor and its tentacles as arms to catch prey. Their foes are melted with a potent acid before being consumed.*

**DexID**:: 0346
**Name**:: Cradily
**Type**:: Rock / Grass
**Abilities**:: [[SRD-Suction Cups|Suction Cups]] ([[SRD-Storm Drain|Storm Drain]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 133.2lbs / 60.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Lileep]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cradily.md"
flatten moves as T
where file.path = this.file.path
```
