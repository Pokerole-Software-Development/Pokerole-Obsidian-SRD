---
Ability1: Drought
Ability2: ''
BookSprite: SRD-groudon-BookSprite.png
BoxSprite: SRD-groudon-BoxSprite.png
DexCategory: No Data
DexDescription: Described in mythology as the God creator of lands, mountains, volcanoes
  and continents. Any water or clouds evaporate in its presence. It is the mortal
  enemy of Kyogre.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Groudon (Primal Form)]]'
GenderType: N
Height:
  Feet: 11.5
  Meters: 3.5
HiddenAbility: ''
HomeSprite: SRD-groudon-HomeSprite.png
Image: groudon.png
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
ShuffleToken: SRD-groudon-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 950.0
  Pounds: 2094.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-groudon-BookSprite.png|wsmall]]
> ![[SRD-groudon-HomeSprite.png]]
> ![[SRD-groudon-BoxSprite.png|htiny]]
> ![[SRD-groudon-ShuffleToken.png|wsmall]]


*No Data*
*Described in mythology as the God creator of lands, mountains, volcanoes and continents. Any water or clouds evaporate in its presence. It is the mortal enemy of Kyogre.*

**DexID**:: 0383
**Name**:: Groudon
**Type**:: Ground
**Abilities**:: [[SRD-Drought|Drought]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 11'5" / 3.5m
**Weight**: 2094.4lbs / 950.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                       | Kind   |
|:----------|:------------------------------|:-------|
| To        | [[SRD-Groudon (Primal Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Groudon.md"
flatten moves as T
where file.path = this.file.path
```
