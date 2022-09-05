---
Accuracy1: Dexterity
Accuracy2: Stealth
Damage1: ''
Damage2: ''
Description: The user lays a trap of scattered poison spikes that attach to the opponent's
  feet leaving them with a bad case of fever.
DmgType: Support
Effect: Foe Pokemon that enter the battlefield become Poisoned. Roll 1 Chance Dice
  for the Poison to become Badly Poisoned instead. Entry Hazard.
Name: Toxic Spikes
Power: 0
Target: Battlefield
Type: Poison
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