---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-rotom-wash-form-BookSprite.png
BoxSprite: SRD-rotom-wash-form-BoxSprite.png
DexCategory: Plasma Pokemon
DexDescription: 'A Washing machine possessed by a Rotom. It uses Water powers and
  floods the houses with torrents of water. While on this form it can use the move:
  Hydro Pump.'
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
HomeSprite: SRD-rotom-wash-form-HomeSprite.png
Image: rotom-wash-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Wave|Thunder Wave]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confuse Ray|Confuse Ray]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Shock|Thunder Shock]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trick|Trick]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double Team|Double Team]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shock Wave|Shock Wave]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Substitute|Substitute]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Electro Ball|Electro Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hex|Hex]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Discharge|Discharge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hydro Pump|Hydro Pump]]'
Number: 479
ShuffleToken: SRD-rotom-wash-form-ShuffleToken.png
Type1: Electric
Type2: Water
Weight:
  Kilograms: 0.3
  Pounds: 0.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rotom-wash-form-BookSprite.png|wsmall]]
> ![[SRD-rotom-wash-form-HomeSprite.png]]
> ![[SRD-rotom-wash-form-BoxSprite.png|htiny]]
> ![[SRD-rotom-wash-form-ShuffleToken.png|wsmall]]


*Plasma Pokemon*
*A Washing machine possessed by a Rotom. It uses Water powers and floods the houses with torrents of water. While on this form it can use the move: Hydro Pump.*

**DexID**:: 0479F5
**Name**:: Rotom (Wash Form)
**Type**:: Electric / Water
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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rotom (Wash Form).md"
flatten moves as T
where file.path = this.file.path
```
