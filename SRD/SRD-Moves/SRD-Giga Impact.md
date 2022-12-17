---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  Lethal: true
  MustRecharge: true
Damage1: Strength
Damage2: ''
Description: The Pokemon strikes with a brutal force using all its body. The impact
  leaves the user somewhat stunned.
DmgType: Physical
Effect: Must Recharge. Lethal. -1 Accuracy.
Name: Giga Impact
Power: 6
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