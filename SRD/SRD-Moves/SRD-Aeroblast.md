---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  HighCritical: true
  Lethal: true
Damage1: Special
Damage2: ''
Description: The victim is trapped in a violently swirling vortex. The strong wind
  currents make debris fly everywhere.
DmgType: Special
Effect: Lethal. High Critical.
Name: Aeroblast
Power: 4
Target: Foe
Type: Flying
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