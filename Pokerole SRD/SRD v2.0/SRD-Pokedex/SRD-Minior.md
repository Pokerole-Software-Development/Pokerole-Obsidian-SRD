---
Ability1: Shields Down
Ability2: ''
BookSprite: SRD-minior-BookSprite.png
BoxSprite: SRD-minior-BoxSprite.png
DexCategory: Meteor Pokemon
DexDescription: They live on the stratosphere, absorbing particles to grow their cores
  and shells, when they become too heavy they fall to the ground. Move damage can
  break the shell and leave the core exposed.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Minior Core]]'
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: ''
HomeSprite: SRD-minior-HomeSprite.png
Image: minior.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Starter
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Beginner
  - '[[SRD-Swift|Swift]]'
- - Beginner
  - '[[SRD-Ancient Power|Ancient Power]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Autotomize|Autotomize]]'
- - Amateur
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Light Screen|Light Screen]]'
- - Pro
  - '[[SRD-Reflect|Reflect]]'
- - Pro
  - '[[SRD-Acrobatics|Acrobatics]]'
Number: 774
ShuffleToken: SRD-minior-ShuffleToken.png
Type1: Rock
Type2: Flying
Weight:
  Kilograms: 40.0
  Pounds: 88.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-minior-BookSprite.png|wsmall]]
> ![[SRD-minior-HomeSprite.png]]
> ![[SRD-minior-BoxSprite.png|htiny]]
> ![[SRD-minior-ShuffleToken.png|wsmall]]


*Meteor Pokemon*
*They live on the stratosphere, absorbing particles to grow their cores and shells, when they become too heavy they fall to the ground. Move damage can break the shell and leave the core exposed.*

**DexID**:: 0774
**Name**:: Minior
**Type**:: Rock / Flying
**Abilities**:: [[SRD-Shields Down|Shields Down]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 1'0" / 0.3m
**Weight**: 88.2lbs / 40.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon             | Kind   |
|:----------|:--------------------|:-------|
| To        | [[SRD-Minior Core]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Minior.md"
flatten moves as T
where file.path = this.file.path
```
