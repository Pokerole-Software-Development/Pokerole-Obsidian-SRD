---
Accuracy1: Clever
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: The Pokemon munches its berry but keeps part of it on its cheeks. Looks
  adorable but it is actually a survival tactic to survive harsh winters.
DmgType: Support
Effect: User eats its held Berry and gains its effects, afterwards, Increase user's
  Defense by 2.
Name: Stuff Cheeks
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