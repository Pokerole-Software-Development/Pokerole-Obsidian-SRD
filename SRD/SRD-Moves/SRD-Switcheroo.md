---
Accuracy1: Insight
Accuracy2: Stealth
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user quickly switches the held items before the foe can realize what
  happened.
DmgType: Support
Effect: User and Foe switch their Held Item. If only one Pokemon is holding an item
  it gives it away.
Name: Switcheroo
Power: 0
Target: Foe
Type: Dark
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