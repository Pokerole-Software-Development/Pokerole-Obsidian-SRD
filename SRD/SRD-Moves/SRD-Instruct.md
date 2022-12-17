---
Accuracy1: Clever
Accuracy2: Perform
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon sends a psychic command to one of its allies or foes to enable
  them to repeat their last action.
DmgType: Support
Effect: Selected Target repeats their last move used this Round, taking the successes
  on the Accuracy Roll of "Instruct" as if they were for their move. Target must have
  previously used a successful move during the Round. Otherwise "Instruct" will fail.
Name: Instruct
Power: 0
Target: Foe
Type: Psychic
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`