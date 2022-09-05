---
Accuracy1: Strength
Accuracy2: Brawl
Damage1: Strength
Damage2: ''
Description: A brutal punch that requires calm and concentration
DmgType: Physical
Effect: Fist Based. Charge Move. The User will flinch if it gets hit before releasing
  this attack.
Name: Focus Punch
Power: 6
Target: Foe
Type: Fighting
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