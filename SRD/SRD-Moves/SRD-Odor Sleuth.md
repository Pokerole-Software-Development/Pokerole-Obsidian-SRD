---
Accuracy1: Insight
Accuracy2: Alert
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: ForesightOdorSleuth
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon uses its keen smell to detect the foe.
DmgType: Support
Effect: The Foe can not Evade moves performed by the User. User's Normal and Fighting
  Moves can affect Ghost Types and Ghost Moves can affect Normal Types. Add all Successes
  from this Move to any Rolls to Track the target.
Name: Odor Sleuth
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