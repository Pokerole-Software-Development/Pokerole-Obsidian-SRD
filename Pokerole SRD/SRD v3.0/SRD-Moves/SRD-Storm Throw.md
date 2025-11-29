---
Accuracy1: Vitality
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  AlwaysCrit: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user throws its foe with a special technique, the foe lands right
  on their weak spot.
Effect: Single Target. This Move is always considered to be a Critical Hit and gets
  the proper Bonus for it.
Name: Storm Throw
Power: 2
Target: Foe
Type: Fighting
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