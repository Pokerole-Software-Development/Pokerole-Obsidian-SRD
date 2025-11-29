---
Accuracy1: Clever
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Imprison
Attributes:
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: This move blocks all shared parts of a memory the user is well aware
  of. Moves, techniques, names, places, people or situations, no one will be able
  to recall those imprisoned memories.
Effect: Target Self. While the User is on the battlefield, Moves known by the User
  cannot be used by foes. This effect ends if the User is removed from battle.
Name: Imprison
Power: 0
Target: Self
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