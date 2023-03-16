---
Ability1: Desolate Land
Ability2: ''
BookSprite: SRD-groudon-primal-form-BookSprite.png
BoxSprite: SRD-groudon-primal-form-BoxSprite.png
DexCategory: No Data
DexDescription: Millions of years ago chaos reigned. Volcanoes erupting without control,
  and unbearable heat made all life dry out. Who was so angry inside the raging fire?
  For its fury has since ingrained into the earth as red rubies.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Groudon]]'
GenderType: N
Height:
  Feet: 16.4
  Meters: 5.0
HiddenAbility: ''
HomeSprite: SRD-groudon-primal-form-HomeSprite.png
Image: groudon-primal-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Master
  - '[[SRD-Rest|Rest]]'
- - Master
  - '[[SRD-Earthquake|Earthquake]]'
- - Master
  - '[[SRD-Precipice Blades|Precipice Blades]]'
- - Master
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Master
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Master
  - '[[SRD-Fissure|Fissure]]'
- - Master
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Eruption|Eruption]]'
- - Master
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Master
  - '[[SRD-Dig|Dig]]'
- - Master
  - '[[SRD-Strength|Strength]]'
- - Master
  - '[[SRD-Block|Block]]'
- - Master
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Master
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Master
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Master
  - '[[SRD-Heat Crash|Heat Crash]]'
- - Master
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Master
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[SRD-Rock Climb|Rock Climb]]'
Number: 383
ShuffleToken: SRD-groudon-primal-form-ShuffleToken.png
Type1: Ground
Type2: Fire
Weight:
  Kilograms: 999.7
  Pounds: 2204.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-groudon-primal-form-BookSprite.png|wsmall]]
> ![[SRD-groudon-primal-form-HomeSprite.png]]
> ![[SRD-groudon-primal-form-BoxSprite.png|htiny]]
> ![[SRD-groudon-primal-form-ShuffleToken.png|wsmall]]


*No Data*
*Millions of years ago chaos reigned. Volcanoes erupting without control, and unbearable heat made all life dry out. Who was so angry inside the raging fire? For its fury has since ingrained into the earth as red rubies.*

**DexID**:: 0383M1
**Name**:: Groudon (Primal Form)
**Type**:: Ground / Fire
**Abilities**:: [[SRD-Desolate Land|Desolate Land]]
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::9)/(MaxStrength::9)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::8)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 16'4" / 5.0m
**Weight**: 2204.0lbs / 999.7kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon         | Kind   |
|:----------|:----------------|:-------|
| From      | [[SRD-Groudon]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Groudon (Primal Form).md"
flatten moves as T
where file.path = this.file.path
```
