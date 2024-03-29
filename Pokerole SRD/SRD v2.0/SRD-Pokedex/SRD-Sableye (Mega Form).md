---
Ability1: Magic Bounce
Ability2: ''
BookSprite: SRD-sableye-mega-form-BookSprite.png
BoxSprite: SRD-sableye-mega-form-BoxSprite.png
DexCategory: Darkness Pokemon
DexDescription: The power of the Mega Stone made the jewel on its chest grow, it now
  uses it as a shield to repel any attack, but its movement is limited due to how
  heavy it is. Its greed for the jewel can make it aggressive.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Sablenite
  Kind: Mega
  Pokemon: '[[SRD-Sableye]]'
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: ''
HomeSprite: SRD-sableye-mega-form-HomeSprite.png
Image: sableye-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mean Look|Mean Look]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scratch|Scratch]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Foresight|Foresight]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Night Shade|Night Shade]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Astonish|Astonish]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fake Out|Fake Out]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Detect|Detect]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Punishment|Punishment]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Foul Play|Foul Play]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confuse Ray|Confuse Ray]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Ball|Shadow Ball]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Moonlight|Moonlight]]'
Number: 302
ShuffleToken: SRD-sableye-mega-form-ShuffleToken.png
Type1: Dark
Type2: Ghost
Weight:
  Kilograms: 161.0
  Pounds: 354.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sableye-mega-form-BookSprite.png|wsmall]]
> ![[SRD-sableye-mega-form-HomeSprite.png]]
> ![[SRD-sableye-mega-form-BoxSprite.png|htiny]]
> ![[SRD-sableye-mega-form-ShuffleToken.png|wsmall]]


*Darkness Pokemon*
*The power of the Mega Stone made the jewel on its chest grow, it now uses it as a shield to repel any attack, but its movement is limited due to how heavy it is. Its greed for the jewel can make it aggressive.*

**DexID**:: 0302M1
**Name**:: Sableye (Mega Form)
**Type**:: Dark / Ghost
**Abilities**:: [[SRD-Magic Bounce|Magic Bounce]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 1'6" / 0.5m
**Weight**: 354.9lbs / 161.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Item      |
|:----------|:----------------|:-------|:----------|
| From      | [[SRD-Sableye]] | Mega   | Sablenite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sableye (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
