---
Accuracy1: SPECIAL
Accuracy2: PERFORM
Damage1: SPECIAL
Damage2: ''
Description: The user sings and dances to a melody so beautiful you won't notice you
  were crying while listening to it.
DmgType: SPECIAL
Effect: Sound Based. Roll 1 Die to put the foe to Sleep. If successful, the User may
  choose to change its form afterwards.
Name: Relic Song
Power: 2
Target: All Foes
Type: Normal
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