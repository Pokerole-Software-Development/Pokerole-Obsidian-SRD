---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: SuppressAbility
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The user spews their gastric juices on the foe. It\u2019s so disgusting\
  \ the foe can only concentrate on getting cleaned ASAP"
Effect: Single Target. Negate any effect the Target's Ability would have. Whole Scene
  Duration.
Name: Gastro Acid
Power: 0
Target: Foe
Type: Poison
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