---
Accuracy1: Will
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The user shares its pain with the foe. After a short while it becomes
  excruciating for the target.
DmgType: Support
Effect: The user gives its Pain Penalizations to the foe. User ignores Pain Penalization
  effects on itself. For cannot ignore them with Will but it can still ignore its
  own Pain Penalizations. HP on both remains the same.
Name: Pain Split
Power: 0
Target: Foe
Type: Normal
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