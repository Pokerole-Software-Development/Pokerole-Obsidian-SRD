---
Ability1: Guts
Ability2: Sheer Force
BookSprite: SRD-conkeldurr-BookSprite.png
BoxSprite: SRD-conkeldurr-BoxSprite.png
DexCategory: Muscular Pokemon
DexDescription: They use concrete pillars as walking canes and swing the pillars freely
  in battle. Anthropology research says that this Pokemon may have taught humans how
  to make concrete out of rocks thousands of years ago.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Trade
  Pokemon: '[[SRD-Gurdurr]]'
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Iron Fist
HomeSprite: SRD-conkeldurr-HomeSprite.png
Image: conkeldurr.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pound|Pound]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Low Kick|Low Kick]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dynamic Punch|Dynamic Punch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Focus Punch|Focus Punch]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Foresight|Foresight]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wide Guard|Wide Guard]]'
Number: 534
ShuffleToken: SRD-conkeldurr-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 87.0
  Pounds: 191.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-conkeldurr-BookSprite.png|wsmall]]
> ![[SRD-conkeldurr-HomeSprite.png]]
> ![[SRD-conkeldurr-BoxSprite.png|htiny]]
> ![[SRD-conkeldurr-ShuffleToken.png|wsmall]]


*Muscular Pokemon*
*They use concrete pillars as walking canes and swing the pillars freely in battle. Anthropology research says that this Pokemon may have taught humans how to make concrete out of rocks thousands of years ago.*

**DexID**:: 0534
**Name**:: Conkeldurr
**Type**:: Fighting
**Abilities**:: [[SRD-Guts|Guts]] / [[SRD-Sheer Force|Sheer Force]] ([[SRD-Iron Fist|Iron Fist]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'6" / 1.4m
**Weight**: 191.8lbs / 87.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   |
|:----------|:----------------|:-------|
| From      | [[SRD-Gurdurr]] | Trade  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Conkeldurr.md"
flatten moves as T
where file.path = this.file.path
```
