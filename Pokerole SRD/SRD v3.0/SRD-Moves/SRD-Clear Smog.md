---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  NeverMiss: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user shoots a blast of venomous pins that inject venom into the foe,
  this venom is specially potent against those already compromised.
Effect: Single Target. Never Miss. Reset all Increased or Reduced Attributes on the
  Foe.
Name: Clear Smog
Power: 2
Target: Foe
Type: Poison
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