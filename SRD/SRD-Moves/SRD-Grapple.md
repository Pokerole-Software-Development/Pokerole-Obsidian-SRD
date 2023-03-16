---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: ''
Effect: The foe is Blocked. Foe can resist this Maneuver by rolling their Strength
  or Dexterity score and scoring the same or more successes than the user.
Name: Grapple
Power: 0
Target: Foe
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