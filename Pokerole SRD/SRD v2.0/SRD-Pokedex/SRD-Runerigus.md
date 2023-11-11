---
Ability1: Wandering Spirit
Ability2: ''
BookSprite: SRD-runerigus-BookSprite.png
BoxSprite: SRD-runerigus-BoxSprite.png
DexCategory: Grudge Pokemon
DexDescription: "A powerful curse was woven into an ancient rune painting, the spirit\
  \ of Yamask is absorbed by this curse and it evolves into a Runerigs. Do not touch\
  \ the shadow parts of its body or you\u2019ll see terrible visions of the past."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Special
  Pokemon: '[[SRD-Yamask (Galarian Form)]]'
  Special: Walk near a rune Painting
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: ''
HomeSprite: SRD-runerigus-HomeSprite.png
Image: runerigus.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Astonish|Astonish]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Haze|Haze]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Night Shade|Night Shade]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Disable|Disable]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Brutal Swing|Brutal Swing]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crafty Shield|Crafty Shield]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hex|Hex]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Claw|Shadow Claw]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slam|Slam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Curse|Curse]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Power Split|Power Split]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Destiny Bond|Destiny Bond]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Guard Split|Guard Split]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Memento|Memento]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stealth Rock|Stealth Rock]]'
Number: 867
ShuffleToken: SRD-runerigus-ShuffleToken.png
Type1: Ground
Type2: Ghost
Weight:
  Kilograms: 66.6
  Pounds: 146.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-runerigus-BookSprite.png|wsmall]]
> ![[SRD-runerigus-HomeSprite.png]]
> ![[SRD-runerigus-BoxSprite.png|htiny]]
> ![[SRD-runerigus-ShuffleToken.png|wsmall]]


*Grudge Pokemon*
*A powerful curse was woven into an ancient rune painting, the spirit of Yamask is absorbed by this curse and it evolves into a Runerigs. Do not touch the shadow parts of its body or you’ll see terrible visions of the past.*

**DexID**:: 0867
**Name**:: Runerigus
**Type**:: Ground / Ghost
**Abilities**:: [[SRD-Wandering Spirit|Wandering Spirit]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 146.8lbs / 66.6kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                        | Kind    | Special                   |
|:----------|:-------------------------------|:--------|:--------------------------|
| From      | [[SRD-Yamask (Galarian Form)]] | Special | Walk near a rune Painting |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Runerigus.md"
flatten moves as T
where file.path = this.file.path
```
