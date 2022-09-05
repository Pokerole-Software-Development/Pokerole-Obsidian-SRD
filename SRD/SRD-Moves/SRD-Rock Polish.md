---
Accuracy1: Dexterity
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The user polishes the rough ends of its rock body for easier and faster
  movement.
DmgType: Support
Effect: Increase User's Dexterity by 2.
Name: Rock Polish
Power: 0
Target: User
Type: Rock
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