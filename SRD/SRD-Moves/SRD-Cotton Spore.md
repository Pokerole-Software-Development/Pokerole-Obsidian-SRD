---
Accuracy1: INSIGHT
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: The Pokemon covers the foe in cotton, disrupting its movement speed.
DmgType: SUPPORT
Effect: Reduce foe's Dexterity by 2.
Name: Cotton Spore
Power: 0
Target: Foe
Type: Grass
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