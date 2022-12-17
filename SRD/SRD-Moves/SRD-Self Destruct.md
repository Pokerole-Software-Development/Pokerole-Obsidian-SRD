---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  UserFaints: true
Damage1: Strength
Damage2: ''
Description: The Pokemon makes use of its ability to blow up parts of its own body
  in an impressive display of power.
DmgType: Physical
Effect: After performing the move, the user receives damage equal to its remaining
  HP.
Name: Self Destruct
Power: 8
Target: Area
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