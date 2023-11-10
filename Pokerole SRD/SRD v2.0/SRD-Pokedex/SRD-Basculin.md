---
Ability1: Reckless
Ability2: Adaptability
BookSprite: SRD-basculin-BookSprite.png
BoxSprite: SRD-basculin-BoxSprite.png
DexCategory: Hostile Pokemon
DexDescription: "Two variants exist of the same Pokemon, a blue one and a red one\
  \ but they don\u2019t get along as they compete for territory and prey. These Pokemon\
  \ are very hostile, but also delicious when grilled."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Mold Breaker
HomeSprite: SRD-basculin-HomeSprite.png
Image: basculin.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - Beginner
  - '[[SRD-Headbutt|Headbutt]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Soak|Soak]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 550
ShuffleToken: SRD-basculin-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 18.0
  Pounds: 39.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-basculin-BookSprite.png|wsmall]]
> ![[SRD-basculin-HomeSprite.png]]
> ![[SRD-basculin-BoxSprite.png|htiny]]
> ![[SRD-basculin-ShuffleToken.png|wsmall]]


*Hostile Pokemon*
*Two variants exist of the same Pokemon, a blue one and a red one but they don’t get along as they compete for territory and prey. These Pokemon are very hostile, but also delicious when grilled.*

**DexID**:: 0550
**Name**:: Basculin
**Type**:: Water
**Abilities**:: [[SRD-Reckless|Reckless]] / [[SRD-Adaptability|Adaptability]] ([[SRD-Mold Breaker|Mold Breaker]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 39.7lbs / 18.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Basculin.md"
flatten moves as T
where file.path = this.file.path
```
