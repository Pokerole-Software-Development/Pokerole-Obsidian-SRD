---
Accuracy1: Dexterity
Accuracy2: Channel
Damage1: Strength
Damage2: ''
Description: The Pokemon rises on top of its foe and drops an apple on their head.
  The foe proceeds to eat the apple, distracting it from the fight.
DmgType: Physical
Effect: Ranged. Reduce the Foe's Defense.
Name: Grav Apple
Power: 3
Target: Foe
Type: Grass
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