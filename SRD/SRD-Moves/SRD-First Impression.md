---
Accuracy1: STRENGTH
Accuracy2: INTIMIDATE
Damage1: STRENGTH
Damage2: ''
Description: The Pokemon makes a dramatic entrance to the battlefield, taking the
  foe by surprise as to who its opponent really is.
DmgType: PHYSICAL
Effect: Priority 2. This move will only work the First Round the Pokemon is out in
  battle. From the second round on it will fail automatically.
Name: First Impression
Power: 3
Target: Foe
Type: Bug
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