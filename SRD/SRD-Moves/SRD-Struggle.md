---
Accuracy1: Dexterity
Accuracy2: BRAWL/CHANNEL
Damage1: Strength/special
Damage2: ''
Description: ''
DmgType: Physical/special
Effect: The most basic attack.
Name: Struggle
Power: 0
Target: Foe
Type: Typeless
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