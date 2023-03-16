---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-spiritomb-BookSprite.png
BoxSprite: SRD-spiritomb-BoxSprite.png
DexCategory: Forbidden Pokemon
DexDescription: A legend from 500 years ago tells how it got bound into an Odd Keystone
  after cursing an entire town. Two have been found in recent times. It is said that
  its vortex has more than 100 haunted souls.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Infiltrator
HomeSprite: SRD-spiritomb-HomeSprite.png
Image: spiritomb.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Curse|Curse]]'
- - Starter
  - '[[SRD-Pursuit|Pursuit]]'
- - Starter
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Starter
  - '[[SRD-Spite|Spite]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Pro
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Pro
  - '[[SRD-Imprison|Imprison]]'
Number: 442
ShuffleToken: SRD-spiritomb-ShuffleToken.png
Type1: Ghost
Type2: Dark
Weight:
  Kilograms: 108.0
  Pounds: 238.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-spiritomb-BookSprite.png|wsmall]]
> ![[SRD-spiritomb-HomeSprite.png]]
> ![[SRD-spiritomb-BoxSprite.png|htiny]]
> ![[SRD-spiritomb-ShuffleToken.png|wsmall]]


*Forbidden Pokemon*
*A legend from 500 years ago tells how it got bound into an Odd Keystone after cursing an entire town. Two have been found in recent times. It is said that its vortex has more than 100 haunted souls.*

**DexID**:: 0442
**Name**:: Spiritomb
**Type**:: Ghost / Dark
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Infiltrator|Infiltrator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'3" / 1.0m
**Weight**: 238.1lbs / 108.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Spiritomb.md"
flatten moves as T
where file.path = this.file.path
```
