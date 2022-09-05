---
Accuracy1: Special
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: The Pokemon roots itself to the ground, absorbing the nutrients and recovering
  health.
DmgType: Support
Effect: User Heals 1 HP at the end of every Round. While this move is active the User
  is now Blocked.
Name: Ingrain
Power: 0
Target: User
Type: Grass
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