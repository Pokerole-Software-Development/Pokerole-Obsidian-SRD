---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: The user calls a floating ember to consume the foe.
DmgType: SUPPORT
Effect: Burn the Foe. -2 Accuracy.
Name: Will-O-Wisp
Power: 0
Target: Foe
Type: Fire
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