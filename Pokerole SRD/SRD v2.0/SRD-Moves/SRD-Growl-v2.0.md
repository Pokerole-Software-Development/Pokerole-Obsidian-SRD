---
Accuracy1: Tough/cute
Accuracy2: PERFORM
Category: Support
Damage1: ''
Damage2: ''
Description: Either by a menacing attitude or cute demeanor, the foe will be unsure
  about attacking the user with full force.
Effect: Reduce the foe's Strength. Sound Based. "Growl (Cute/Tough)", the user should
  use the one with highest stat (tough / cute)
Name: Growl
Power: 0
Target: All Foes
Type: Normal
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