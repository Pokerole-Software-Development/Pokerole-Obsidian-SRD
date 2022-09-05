---
Accuracy1: Special
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: Inside the effects of Magic Room, technology, tools, and items manually
  activated do not work. Automated technology will function as normal.
DmgType: Support
Effect: No one can use their Held Item nor any other Item. Lasts 4 Rounds.
Name: Magic Room
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