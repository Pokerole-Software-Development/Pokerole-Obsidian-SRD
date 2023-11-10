---
Ability1: Prankster
Ability2: ''
BookSprite: SRD-banette-mega-form-BookSprite.png
BoxSprite: SRD-banette-mega-form-BoxSprite.png
DexCategory: Marionette Pokemon
DexDescription: "The power of the Mega Stone rips the layer keeping all the cursed\
  \ energy in. Its vindictive nature is so overwhelming that it can\u2019t help but\
  \ to curse its own Trainer."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Banettite
  Kind: Mega
  Pokemon: '[[SRD-Banette]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: ''
HomeSprite: SRD-banette-mega-form-HomeSprite.png
Image: banette-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Knock Off|Knock Off]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Spite|Spite]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Amateur
  - '[[SRD-Snatch|Snatch]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Trick|Trick]]'
- - Ace
  - '[[SRD-Phantom Force|Phantom Force]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Role Play|Role Play]]'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
Number: 354
ShuffleToken: SRD-banette-mega-form-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 13.0
  Pounds: 28.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-banette-mega-form-BookSprite.png|wsmall]]
> ![[SRD-banette-mega-form-HomeSprite.png]]
> ![[SRD-banette-mega-form-BoxSprite.png|htiny]]
> ![[SRD-banette-mega-form-ShuffleToken.png|wsmall]]


*Marionette Pokemon*
*The power of the Mega Stone rips the layer keeping all the cursed energy in. Its vindictive nature is so overwhelming that it can’t help but to curse its own Trainer.*

**DexID**:: 0354M1
**Name**:: Banette (Mega Form)
**Type**:: Ghost
**Abilities**:: [[SRD-Prankster|Prankster]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 28.7lbs / 13.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Item      |
|:----------|:----------------|:-------|:----------|
| From      | [[SRD-Banette]] | Mega   | Banettite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Banette (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
