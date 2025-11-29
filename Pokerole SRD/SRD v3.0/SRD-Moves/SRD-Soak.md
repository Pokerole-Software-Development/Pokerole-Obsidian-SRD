---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    TargetType: Water
    Type: ChangedType
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The foe gets soaking wet, they should stay away from electric outlets
  and thirsty plants.
Effect: Single Target. Change the Target's Type to Water. (ie Charizard was Fire/Flying,
  after this Move their Type will be Water) Whole Scene Duration. This effect does
  not end by switching out the affected Pokemon.
Name: Soak
Power: 0
Target: Foe
Type: Water
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