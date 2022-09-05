---
Accuracy1: ''
Accuracy2: ''
Damage1: ''
Damage2: ''
Description: After falling asleep, the Pokemon is still dreaming about the fight.
DmgType: Support
Effect: While this Pokemon is asleep, it may use one of its Moves at random.
Name: Sleep Talk
Power: 0
Target: Random Foe
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