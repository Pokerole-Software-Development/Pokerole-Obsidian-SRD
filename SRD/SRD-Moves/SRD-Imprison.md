---
Accuracy1: Clever
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Imprison
Attributes: {}
Damage1: ''
Damage2: ''
Description: This move blocks specific parts of the memory the user is well aware
  of. Be it moves, techniques, names, places, people, or situations. The target won't
  be able to recall those memories.
DmgType: Support
Effect: The foe cannot use any Moves known by the User. Lasts for a day.
Name: Imprison
Power: 0
Target: Foe
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