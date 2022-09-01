---
Accuracy1: SPECIAL
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: A blow of dust that paralyzes the target on the spot and cramps its muscles.
DmgType: SUPPORT
Effect: Paralyze the Foe. -2 Accuracy.
Name: Stun Spore
Power: 0
Target: Foe
Type: Grass
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