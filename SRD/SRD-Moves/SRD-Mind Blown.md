---
Accuracy1: INSIGHT
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The Pokemon has had a terrible day and has a very bad headache, try not
  to disturb its peace because its head feels like exploding.
DmgType: SPECIAL
Effect: Area Attack. Recoil.
Name: Mind Blown
Power: 6
Target: Area
Type: Fire
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