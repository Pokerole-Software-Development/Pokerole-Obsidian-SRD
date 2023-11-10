---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-rotom-mow-form-BookSprite.png
BoxSprite: SRD-rotom-mow-form-BoxSprite.png
DexCategory: Plasma Pokemon
DexDescription: 'A Lawnmower possessed by a Rotom. It uses Grass powers, mows awful
  patterns on the grass and chases people with the blades out. While on this form
  it can use the move: Leaf Storm.'
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Rotom]]'
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: ''
HomeSprite: SRD-rotom-mow-form-HomeSprite.png
Image: rotom-mow-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Trick|Trick]]'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Substitute|Substitute]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hex|Hex]]'
- - Ace
  - '[[SRD-Charge|Charge]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Leaf Storm|Leaf Storm]]'
Number: 479
ShuffleToken: SRD-rotom-mow-form-ShuffleToken.png
Type1: Electric
Type2: Grass
Weight:
  Kilograms: 0.3
  Pounds: 0.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rotom-mow-form-BookSprite.png|wsmall]]
> ![[SRD-rotom-mow-form-HomeSprite.png]]
> ![[SRD-rotom-mow-form-BoxSprite.png|htiny]]
> ![[SRD-rotom-mow-form-ShuffleToken.png|wsmall]]


*Plasma Pokemon*
*A Lawnmower possessed by a Rotom. It uses Grass powers, mows awful patterns on the grass and chases people with the blades out. While on this form it can use the move: Leaf Storm.*

**DexID**:: 0479F3
**Name**:: Rotom (Mow Form)
**Type**:: Electric / Grass
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 1'0" / 0.3m
**Weight**: 0.7lbs / 0.3kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon       | Kind   |
|:----------|:--------------|:-------|
| From      | [[SRD-Rotom]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rotom (Mow Form).md"
flatten moves as T
where file.path = this.file.path
```
