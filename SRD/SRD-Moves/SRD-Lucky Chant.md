---
Accuracy1: Special
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: LuckyChant
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user chants an incantation to the skies. The beautiful performance
  grants this Pokemon and its allies divine protection.
Effect: User and Allies in range can re-roll one un-successful die from all their
  rolls until the end of the scene. If an opponent would land a Critical Hit it doesn't.
  Outside of battle good things happen at the story tellers discretion.
Name: Lucky Chant
Power: 0
Target: User and Allies
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