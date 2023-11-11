---
Ability1: Water Absorb
Ability2: Ice Body
BookSprite: SRD-arctovish-BookSprite.png
BoxSprite: SRD-arctovish-BoxSprite.png
DexCategory: Fossil Pokemon
DexDescription: "This mix of DNA made a more stable creature able to move, breathe\
  \ and resist cold weather, the only problem is that its head is upside down. If\
  \ it\u2019s not fed it cannot hunt on its own and will die of hunger in a few days."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Slush Rush
HomeSprite: SRD-arctovish-HomeSprite.png
Image: arctovish.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Powder Snow|Powder Snow]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aurora Veil|Aurora Veil]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Freeze Dry|Freeze Dry]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Super Fang|Super Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fishious Rend|Fishious Rend]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Icicle Crash|Icicle Crash]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Liquidation|Liquidation]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic Fangs|Psychic Fangs]]'
Number: 883
ShuffleToken: SRD-arctovish-ShuffleToken.png
Type1: Water
Type2: Ice
Weight:
  Kilograms: 175.0
  Pounds: 385.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-arctovish-BookSprite.png|wsmall]]
> ![[SRD-arctovish-HomeSprite.png]]
> ![[SRD-arctovish-BoxSprite.png|htiny]]
> ![[SRD-arctovish-ShuffleToken.png|wsmall]]


*Fossil Pokemon*
*This mix of DNA made a more stable creature able to move, breathe and resist cold weather, the only problem is that its head is upside down. If it’s not fed it cannot hunt on its own and will die of hunger in a few days.*

**DexID**:: 0883
**Name**:: Arctovish
**Type**:: Water / Ice
**Abilities**:: [[SRD-Water Absorb|Water Absorb]] / [[SRD-Ice Body|Ice Body]] ([[SRD-Slush Rush|Slush Rush]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 385.8lbs / 175.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Arctovish.md"
flatten moves as T
where file.path = this.file.path
```
