---
Accuracy1: Will
Accuracy2: Charm
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The user invites their foe to go trick-or-treating. The foe puts on\
  \ a ghost costume that cannot be removed without an exorcism or help from the Pok\xE9\
  mon center."
Effect: Single Target. Add the Ghost Type to the Target's Type. (ie Pikachu will now
  be "Electric/Ghost", Charizard will not be "Fire/Flying/Ghost") If the Target already
  has a third Type attached, replace it.
Name: Trick-Or-Treat
Power: 0
Target: Foe
Type: Ghost
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