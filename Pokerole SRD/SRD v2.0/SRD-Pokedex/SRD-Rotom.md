---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-rotom-BookSprite.png
BoxSprite: SRD-rotom-BoxSprite.png
DexCategory: Plasma Pokemon
DexDescription: Its electric-like body can enter some kinds of machines and take control
  of them in order to cause mischief. It changes its form to that of the electric
  appliance, allowing it to become more powerful.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Rotom (Heat Form)]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Rotom (Fan Form)]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Rotom (Mow Form)]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Rotom (Frost Form)]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Rotom (Wash Form)]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Rotom (Dex Form)]]'
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: ''
HomeSprite: SRD-rotom-HomeSprite.png
Image: rotom.png
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
Number: 479
ShuffleToken: SRD-rotom-ShuffleToken.png
Type1: Electric
Type2: Ghost
Weight:
  Kilograms: 0.3
  Pounds: 0.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rotom-BookSprite.png|wsmall]]
> ![[SRD-rotom-HomeSprite.png]]
> ![[SRD-rotom-BoxSprite.png|htiny]]
> ![[SRD-rotom-ShuffleToken.png|wsmall]]


*Plasma Pokemon*
*Its electric-like body can enter some kinds of machines and take control of them in order to cause mischief. It changes its form to that of the electric appliance, allowing it to become more powerful.*

**DexID**:: 0479
**Name**:: Rotom
**Type**:: Electric / Ghost
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'0" / 0.3m
**Weight**: 0.7lbs / 0.3kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                    | Kind   |
|:----------|:---------------------------|:-------|
| To        | [[SRD-Rotom (Heat Form)]]  | Form   |
| To        | [[SRD-Rotom (Fan Form)]]   | Form   |
| To        | [[SRD-Rotom (Mow Form)]]   | Form   |
| To        | [[SRD-Rotom (Frost Form)]] | Form   |
| To        | [[SRD-Rotom (Wash Form)]]  | Form   |
| To        | [[SRD-Rotom (Dex Form)]]   | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rotom.md"
flatten moves as T
where file.path = this.file.path
```
