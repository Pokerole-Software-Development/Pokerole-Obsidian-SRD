---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Sleep
Attributes:
  AccuracyReduction: 3
Damage1: ''
Damage2: ''
Description: A portal opens and transports all foes to a world of darkness, inside
  they can't see or feel anything, it's like they are trapped in an eternal slumber.
DmgType: Support
Effect: All Foes in Range have the Sleep condition.  -3 Accuracy.
Name: Dark Void
Power: 0
Target: All Foes
Type: Dark
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