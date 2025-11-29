---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 2
    Stages: -1
    Stats:
    - Def
Attributes:
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon gets close to its foe then strikes while bursting a full-force
  blast of pressurized water, the water may cut or dent through the foe's armor.
Effect: Lethal. Roll 2 Chance Dice to Reduce the Foe's Defense.
Name: Liquidation
Power: 3
Target: Foe
Type: Water
---

#PokeroleSRD/Moves

### `= this.name`
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`