---
Ability1: Shell Armor
Ability2: ''
BookSprite: SRD-turtonator-BookSprite.png
BoxSprite: SRD-turtonator-BoxSprite.png
DexCategory: Blast Turtle Pokemon
DexDescription: It leaves in the volcanic areas of Alola, where it disguises itself
  among the rocks, waiting for prey to step on it to detonate an explosion. The hole
  on its chest is a weak point, but it is very difficult to access.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: ''
HomeSprite: SRD-turtonator-HomeSprite.png
Image: turtonator.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smog|Smog]]'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Incinerate|Incinerate]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Amateur
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Shell Trap|Shell Trap]]'
- - Ace
  - '[[SRD-Overheat|Overheat]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Head Smash|Head Smash]]'
- - Pro
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
Number: 776
ShuffleToken: SRD-turtonator-ShuffleToken.png
Type1: Fire
Type2: Dragon
Weight:
  Kilograms: 212.0
  Pounds: 467.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-turtonator-BookSprite.png|wsmall]]
> ![[SRD-turtonator-HomeSprite.png]]
> ![[SRD-turtonator-BoxSprite.png|htiny]]
> ![[SRD-turtonator-ShuffleToken.png|wsmall]]


*Blast Turtle Pokemon*
*It leaves in the volcanic areas of Alola, where it disguises itself among the rocks, waiting for prey to step on it to detonate an explosion. The hole on its chest is a weak point, but it is very difficult to access.*

**DexID**:: 0776
**Name**:: Turtonator
**Type**:: Fire / Dragon
**Abilities**:: [[SRD-Shell Armor|Shell Armor]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 467.4lbs / 212.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Turtonator.md"
flatten moves as T
where file.path = this.file.path
```
