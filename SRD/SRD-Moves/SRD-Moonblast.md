---
Accuracy1: Special
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: Summon power directly from the moon. The Pokemon blasts the foe with
  light.
DmgType: Special
Effect: Roll 3 Chance Dice to Reduce foe's Special.
Name: Moonblast
Power: 3
Target: Foe
Type: Fairy
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