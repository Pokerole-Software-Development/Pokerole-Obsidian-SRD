---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: Target
    Stages: 1
    Stats:
    - Def
    - SpDef
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon showers an ally in a mist with a revitalizing armoa.
DmgType: Support
Effect: Increase one Ally's Defense and Sp. Defense.
Name: Aromatic Mist
Power: 0
Target: One Ally
Type: Fairy
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