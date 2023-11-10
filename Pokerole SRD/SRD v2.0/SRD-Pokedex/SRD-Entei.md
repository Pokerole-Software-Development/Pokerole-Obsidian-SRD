---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-entei-BookSprite.png
BoxSprite: SRD-entei-BoxSprite.png
DexCategory: No Data
DexDescription: Johto Legends tell about a Pokemon so powerful, its bark makes volcanoes
  erupt, traveling the lands cloaked in a cloud of volcanic smoke.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: Inner Focus
HomeSprite: SRD-entei-HomeSprite.png
Image: entei.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Ember|Ember]]'
- - Master
  - '[[SRD-Roar|Roar]]'
- - Master
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Master
  - '[[SRD-Stomp|Stomp]]'
- - Master
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Master
  - '[[SRD-Swagger|Swagger]]'
- - Master
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Master
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Eruption|Eruption]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Substitute|Substitute]]'
- - Master
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Master
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Master
  - '[[SRD-Mimic|Mimic]]'
- - Master
  - '[[SRD-Curse|Curse]]'
- - Master
  - '[[SRD-Sacred Fire|Sacred Fire]]'
Number: 244
ShuffleToken: SRD-entei-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 198.0
  Pounds: 436.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-entei-BookSprite.png|wsmall]]
> ![[SRD-entei-HomeSprite.png]]
> ![[SRD-entei-BoxSprite.png|htiny]]
> ![[SRD-entei-ShuffleToken.png|wsmall]]


*No Data*
*Johto Legends tell about a Pokemon so powerful, its bark makes volcanoes erupt, traveling the lands cloaked in a cloud of volcanic smoke.*

**DexID**:: 0244
**Name**:: Entei
**Type**:: Fire
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Inner Focus|Inner Focus]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 6'9" / 2.1m
**Weight**: 436.5lbs / 198.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Entei.md"
flatten moves as T
where file.path = this.file.path
```
