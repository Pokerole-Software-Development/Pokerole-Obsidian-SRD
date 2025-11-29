---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 5
    Stages: -1
    Stats:
    - Special
Attributes:
  ProjectileMove: true
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The user engulfs its foe with a cloud, this soothing mist keeps evil\
  \ intents from surfacing ino the Target\u2019s mind."
Effect: Single Target. Unique. Projectile Move. Roll 5 Chance Dice to Reduce the Target's
  Special by 1. *This Effect can be stacked up to 3 times per target.
Name: Mist Ball
Power: 2
Target: Foe
Type: Psychic
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