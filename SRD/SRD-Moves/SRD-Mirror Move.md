---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user concentrates and manages to imitate the last move used by the
  foe.
Effect: Copies the last Damaging Move the foe has performed.
Name: Mirror Move
Power: 0
Target: Foe
Type: Flying
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`