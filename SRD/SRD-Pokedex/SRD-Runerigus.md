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
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Haze|Haze]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Amateur
  - '[[SRD-Crafty Shield|Crafty Shield]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Shadow Claw|Shadow Claw]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Power Split|Power Split]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Ace
  - '[[SRD-Guard Split|Guard Split]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Memento|Memento]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
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
FROM "SRD/SRD-Pokedex/SRD-Runerigus.md"
flatten moves as T
where file.path = this.file.path
```
