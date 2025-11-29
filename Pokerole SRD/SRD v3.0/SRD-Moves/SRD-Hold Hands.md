---
Accuracy1: Cool
Accuracy2: Charm
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The user offers their hand in friendship, if the other Pok\xE9mon holds\
  \ their hand they\u2019ll be very happy and become good friends."
Effect: Single Target. The battle may end at the Storyteller's discretion. Target
  may resist rolling their Will Score against the Accuracy of this Move. Out of battle,
  aid to reduce hostile intent.
Name: Hold Hands
Power: 0
Target: Foe
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