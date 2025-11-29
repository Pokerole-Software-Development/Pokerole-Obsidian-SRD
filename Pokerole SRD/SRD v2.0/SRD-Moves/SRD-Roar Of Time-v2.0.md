---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  Lethal: true
  MustRecharge: true
Category: Special
Damage1: Special
Damage2: ''
Description: Through a terrifying roar, Dialga bounds the forces of time on a single
  area, the unfortunate target will be trapped in a time warp, growing old in a matter
  of seconds.
Effect: Lethal. If successful, the target can't have any action until next Round.
  -1 Accuracy.
Name: Roar Of Time
Power: 6
Target: Foe
Type: Dragon
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