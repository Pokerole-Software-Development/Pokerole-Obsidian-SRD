---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Special
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user radiates electricity around itself, the foe will think twice
  about attacking.
DmgType: Support
Effect: Reduce foe's Special by 2.
Name: Eerie Impulse
Power: 0
Target: Foe
Type: Electric
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