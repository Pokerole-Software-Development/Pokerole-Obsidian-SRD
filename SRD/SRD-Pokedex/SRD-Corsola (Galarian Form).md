---
Ability1: Weak Armor
Ability2: ''
BookSprite: SRD-corsola-galarian-form-BookSprite.png
BoxSprite: SRD-corsola-galarian-form-BoxSprite.png
DexCategory: Coral Pokemon
DexDescription: Watch your step when walking through shallow ocean waters  because
  this Pokemon looks like a stone and it will curse you if you kick it. Sudden climate
  change wiped out this ancient kind of Corsola.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Cursola]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Cursed Body
HomeSprite: SRD-corsola-galarian-form-HomeSprite.png
Image: corsola-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Disable|Disable]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spite|Spite]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Strength Sap|Strength Sap]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Power Gem|Power Gem]]'
- - Ace
  - '[[SRD-Night Shade|Night Shade]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Pro
  - '[[SRD-Head Smash|Head Smash]]'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
Number: 222
ShuffleToken: SRD-corsola-galarian-form-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 0.5
  Pounds: 1.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-corsola-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-corsola-galarian-form-HomeSprite.png]]
> ![[SRD-corsola-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-corsola-galarian-form-ShuffleToken.png|wsmall]]


*Coral Pokemon*
*Watch your step when walking through shallow ocean waters  because this Pokemon looks like a stone and it will curse you if you kick it. Sudden climate change wiped out this ancient kind of Corsola.*

**DexID**:: 0222G
**Name**:: Corsola (Galarian Form)
**Type**:: Ghost
**Abilities**:: [[SRD-Weak Armor|Weak Armor]] ([[SRD-Cursed Body|Cursed Body]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 2'0" / 0.6m
**Weight**: 1.1lbs / 0.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Cursola]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Corsola (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
