---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The user gives a hard peck and may get something tasty out of the foe.
DmgType: Physical
Effect: If the Target is holding a Berry, the User eats it and gains its effects.
Name: Pluck
Power: 2
Target: Foe
Type: Flying
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