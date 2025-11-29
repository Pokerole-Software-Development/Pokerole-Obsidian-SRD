---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 3
    Stages: -1
    Stats:
    - Accuracy
Attributes:
  AccuracyReduction: -2
  ProjectileMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon shoots a ball of mud to burst on their victim\u2019s\
  \ face in an attempt to blind them."
Effect: Single Target. Low Accuracy 2. Projectile Move. Roll 3 Chance Die to Reduce
  1 success to all Accuracy rolls of the Target.
Name: Mud Bomb
Power: 2
Target: Foe
Type: Ground
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