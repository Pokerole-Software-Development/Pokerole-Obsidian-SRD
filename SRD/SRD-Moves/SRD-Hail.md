---
Accuracy1: SPECIAL
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: The user summons a hailstorm that will stay on the battlefield for some
  time.
DmgType: SUPPORT
Effect: Hail Weather is activated for the next 4 Rounds.
Name: Hail
Power: 0
Target: Battlefield
Type: Ice
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