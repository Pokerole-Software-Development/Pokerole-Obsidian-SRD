---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 1
    Stages: -1
    Stats:
    - SpDef
Attributes:
  AccuracyReduction: 2
Damage1: Special
Damage2: ''
Description: The user concentrates and releases a blast of energy.
DmgType: Special
Effect: Roll 1 Chance Dice to Reduce foe's Sp. Defense. -2 Accuracy.
Name: Focus Blast
Power: 5
Target: Foe
Type: Fighting
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`