---
Accuracy1: Strength/Special
Accuracy2: Clash
AddedEffects: {}
Attributes:
  Reaction: 6
Category: Support
Damage1: ''
Damage2: ''
Description: A power struggle can become a clash of mights, usually with explosive
  results.
Effect: Target Self. Reaction 6. Match the number of successes on the Accuracy roll
  ofa Move that targets the User. If successful, the user Clashes, see p.68. This
  Maneuver is not affected by the Multiple Action difficulty chart.
Name: Clash
Power: 0
Target: User
Type: Typeless
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