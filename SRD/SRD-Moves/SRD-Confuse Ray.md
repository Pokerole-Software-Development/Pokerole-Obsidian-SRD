---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Confuse
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user flashes a sinister ray of bright light that leaves the target
  disoriented and confused.
DmgType: Support
Effect: Confuse the foe.
Name: Confuse Ray
Power: 0
Target: Foe
Type: Ghost
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