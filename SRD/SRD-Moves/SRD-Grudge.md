---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user leaves an imprinting grudge over the foe, this makes the target
  unwilling to fight. It may only keep battling if something greater is at risk.
DmgType: Support
Effect: The User Faints. The foe gets its Will depleted and any effects gained from
  spending them. The Foe must roll Loyalty at the end of every Round to keep battling.
  Each Round 1 more success is required.
Name: Grudge
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