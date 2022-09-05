---
Accuracy1: Special
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The user forces everyone's wounds to stay open by using its immense psychic
  power.
DmgType: Support
Effect: No one can regain any lost HP. Lasts 4 Rounds.
Name: Heal Block
Power: 0
Target: Area
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