---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  ResistedWithDefense: true
Category: Special
Damage1: Special
Damage2: ''
Description: Materialize a psychic wave that pushes the target with real physical
  force.
Effect: This Move is resisted with the Foe's Defense instead of its Sp. Defense
Name: Psyshock
Power: 3
Target: Foe
Type: Psychic
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