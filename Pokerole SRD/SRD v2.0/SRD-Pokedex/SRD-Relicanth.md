---
Ability1: Swift Swim
Ability2: Rock Head
BookSprite: SRD-relicanth-BookSprite.png
BoxSprite: SRD-relicanth-BoxSprite.png
DexCategory: Longevity Pokemon
DexDescription: It has remained unchanged for millions of years. Relicanth was discovered
  in a deep sea expedition. It feeds on plankton. Their scales are like craggy rocks,
  they can endure the pressure of the deep sea.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Sturdy
HomeSprite: SRD-relicanth-HomeSprite.png
Image: relicanth.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Flail|Flail]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Skull Bash|Skull Bash]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Magnitude|Magnitude]]'
Number: 369
ShuffleToken: SRD-relicanth-ShuffleToken.png
Type1: Water
Type2: Rock
Weight:
  Kilograms: 23.4
  Pounds: 51.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-relicanth-BookSprite.png|wsmall]]
> ![[SRD-relicanth-HomeSprite.png]]
> ![[SRD-relicanth-BoxSprite.png|htiny]]
> ![[SRD-relicanth-ShuffleToken.png|wsmall]]


*Longevity Pokemon*
*It has remained unchanged for millions of years. Relicanth was discovered in a deep sea expedition. It feeds on plankton. Their scales are like craggy rocks, they can endure the pressure of the deep sea.*

**DexID**:: 0369
**Name**:: Relicanth
**Type**:: Water / Rock
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Rock Head|Rock Head]] ([[SRD-Sturdy|Sturdy]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 51.6lbs / 23.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Relicanth.md"
flatten moves as T
where file.path = this.file.path
```
