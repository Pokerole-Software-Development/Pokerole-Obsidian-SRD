---
Ability1: Water Absorb
Ability2: ''
BookSprite: SRD-volcanion-BookSprite.png
BoxSprite: SRD-volcanion-BoxSprite.png
DexCategory: No Data
DexDescription: In the early days of world exploring, there are records of an entire
  mountain blowing up in a cloud of steam. The explorers claimed that a creature in
  the fog was responsible.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-volcanion-HomeSprite.png
Image: volcanion.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Master
  - '[[SRD-Take Down|Take Down]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Haze|Haze]]'
- - Master
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Stomp|Stomp]]'
- - Master
  - '[[SRD-Scald|Scald]]'
- - Master
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Master
  - '[[SRD-Body Slam|Body Slam]]'
- - Master
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[SRD-Overheat|Overheat]]'
- - Master
  - '[[SRD-Explosion|Explosion]]'
- - Master
  - '[[SRD-Steam Eruption|Steam Eruption]]'
- - Master
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
Number: 721
ShuffleToken: SRD-volcanion-ShuffleToken.png
Type1: Fire
Type2: Water
Weight:
  Kilograms: 195.0
  Pounds: 429.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-volcanion-BookSprite.png|wsmall]]
> ![[SRD-volcanion-HomeSprite.png]]
> ![[SRD-volcanion-BoxSprite.png|htiny]]
> ![[SRD-volcanion-ShuffleToken.png|wsmall]]


*No Data*
*In the early days of world exploring, there are records of an entire mountain blowing up in a cloud of steam. The explorers claimed that a creature in the fog was responsible.*

**DexID**:: 0721
**Name**:: Volcanion
**Type**:: Fire / Water
**Abilities**:: [[SRD-Water Absorb|Water Absorb]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 429.9lbs / 195.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Volcanion.md"
flatten moves as T
where file.path = this.file.path
```
