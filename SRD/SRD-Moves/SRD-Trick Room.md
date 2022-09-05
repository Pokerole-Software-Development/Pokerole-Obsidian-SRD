---
Accuracy1: Special
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: This reality altering move can manipulate time, so slow creatures are
  fast, and fast creatures are slow.
DmgType: Support
Effect: Invert the order of Initiative. Lasts 4 Rounds.
Name: Trick Room
Power: 0
Target: Battlefield
Type: Psychic
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