---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: STRENGTH
Damage2: ''
Description: The Pokemon covers the foe in gravel and rocks, leaving it unable to
  move freely.
DmgType: PHYSICAL
Effect: Ranged. Reduce Foe's Dexterity. -1 Accuracy.
Name: Rock Tomb
Power: 2
Target: Foe
Type: Rock
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