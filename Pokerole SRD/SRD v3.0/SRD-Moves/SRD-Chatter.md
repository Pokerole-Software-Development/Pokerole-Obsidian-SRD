---
Accuracy1: Insight
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Confuse
Attributes:
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon parrots the voice of a human and starts issuing silly\
  \ commands to the foe. This quickly becomes confusing for the foe."
Effect: Single Target. Sound Move. Roll 3 Chance Dice to Confuse the Target.
Name: Chatter
Power: 2
Target: Foe
Type: Flying
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