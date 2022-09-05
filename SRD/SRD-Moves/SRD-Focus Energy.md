---
Accuracy1: Insight
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The Pokemon's energy is raised to make all strikes much more precise.
DmgType: Support
Effect: All of the user's damage moves now have High Critical. This effect lasts until
  end of scene or the user is removed from battle.
Name: Focus Energy
Power: 0
Target: User
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