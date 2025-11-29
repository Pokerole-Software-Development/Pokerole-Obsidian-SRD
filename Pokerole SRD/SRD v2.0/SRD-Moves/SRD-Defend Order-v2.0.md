---
Accuracy1: Tough
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: 1
    Stats:
    - Defense
    - SpDefense
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: A swarm of bugs flies around the user, creating a barrier to protect
  this Pokemon from damage.
Effect: User Increases its Defense and Sp. Defense.
Name: Defend Order
Power: 0
Target: User
Type: Bug
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