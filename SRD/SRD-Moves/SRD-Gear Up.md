---
Accuracy1: VITALITY
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: The user engages its gears on an ally to leave the ally's body working
  like a welloiled machine.
DmgType: SUPPORT
Effect: Increase the Strength and Special of one Steel-Type or Electric-Type Ally.
Name: Gear Up
Power: 0
Target: One Ally
Type: Steel
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