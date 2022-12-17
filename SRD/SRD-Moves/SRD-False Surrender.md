---
Accuracy1: Insight
Accuracy2: Allure
AddedEffects: {}
Attributes:
  NeverFail: true
Damage1: Strength
Damage2: ''
Description: The Pokemon bows in defeat, begging for forgiveness, then backstabs its
  gullible foe.
DmgType: Physical
Effect: Never Fail.
Name: False Surrender
Power: 3
Target: Foe
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