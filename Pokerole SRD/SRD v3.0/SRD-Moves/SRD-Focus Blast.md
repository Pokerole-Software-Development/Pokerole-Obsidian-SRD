---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 1
    Stages: -1
    Stats:
    - SpDef
Attributes:
  AccuracyReduction: -2
  ProjectileMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "A powerful energy blast that requires the user to chant each syllabe\
  \ of the technique\u2019s name and release it by yelling \u201CHaaaaa!\u201D"
Effect: Single Target. Low Accuracy 2. Projectile Move. Roll 1 Chance die to Reduce
  the foe's Sp. Defense by 1.
Name: Focus Blast
Power: 5
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