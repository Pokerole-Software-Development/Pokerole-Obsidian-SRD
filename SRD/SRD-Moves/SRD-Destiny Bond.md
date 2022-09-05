---
Accuracy1: Will
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The Pokemon creates a mystical bond with anyone that causes it harm.
  Whatever ill falls on the user, it falls on the perpetrator too.
DmgType: Support
Effect: If the user faints this Round due to Combat damage, the Pokemon that dealt
  the damage will faint at the same time.
Name: Destiny Bond
Power: 0
Target: User
Type: Ghost
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