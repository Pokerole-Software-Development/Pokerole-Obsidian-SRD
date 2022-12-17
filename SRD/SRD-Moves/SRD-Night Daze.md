---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 4
    Stages: -1
    Stats:
    - Accuracy
Attributes: {}
Damage1: Special
Damage2: ''
Description: The user forms a pitch black wave that hurts the foe. This darkness may
  remain obstructing the target's vision.
DmgType: Special
Effect: Roll 4 Chance Dice to Reduce foe's Accuracy.
Name: Night Daze
Power: 3
Target: Foe
Type: Dark
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