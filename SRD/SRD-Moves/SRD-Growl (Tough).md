---
Accuracy1: Tough
Accuracy2: Perform
Damage1: ''
Damage2: ''
Description: The user exhibits a menacing attitude, making the foe unsure about attacking
  the user with full force.
DmgType: Support
Effect: Reduce the foe's Strength. Sound Based. Same move as "Growl (Cute)", the user
  should use the one with highest stat (tough / cute)
Name: Growl (Tough)
Power: 0
Target: All Foes
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