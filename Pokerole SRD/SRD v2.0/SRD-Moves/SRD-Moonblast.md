---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 3
    Stages: -1
    Stats:
    - Special
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: Summon power directly from the moon. The Pokemon blasts the foe with
  light.
Effect: Roll 3 Chance Dice to Reduce foe's Special.
Name: Moonblast
Power: 3
Target: Foe
Type: Fairy
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