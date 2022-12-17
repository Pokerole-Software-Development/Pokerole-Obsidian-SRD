---
Accuracy1: Cool
Accuracy2: Allure
AddedEffects: {}
Attributes:
  Priority: 3
Damage1: ''
Damage2: ''
Description: The user claps and cheers at the target to encourage it to repeat what
  it just did.
DmgType: Support
Effect: For the duration of this effect, the target will repeat the exact same action
  sequence it had this round. Target must have had an action sequence. Last 4 Rounds.
  Priority 3.
Name: Encore
Power: 0
Target: Foe
Type: Normal
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