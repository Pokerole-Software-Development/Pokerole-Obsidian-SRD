---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 4
    Stages: -1
    Stats:
    - Accuracy
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The foe is engulfed by a pitch-black darkness that obscure its vision
  and torments its mind.
Effect: Single Target. Roll 4 Chance Dice to Reduce 1 Success from all Accuracy rolls
  of the foe. Outside of battle, obscuring effects last for a whole scene.
Name: Night Daze
Power: 3
Target: Foe
Type: Dark
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