---
Accuracy1: WILL
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: The user enters the target's dream to torment it.
DmgType: SUPPORT
Effect: Will only work if the Target is asleep. Deal 1 Damage to the foe. Deal 1 Damage
  again at the beginning of each Round if the target is still asleep.
Name: Nightmare
Power: 0
Target: Foe
Type: Ghost
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`