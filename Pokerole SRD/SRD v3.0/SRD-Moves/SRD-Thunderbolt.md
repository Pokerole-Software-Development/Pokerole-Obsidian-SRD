---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Paralyze
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: A solid electric shock. A discharge of nearly 10,000 volts that can knock
  out most foes and destroy electrical devices.
Effect: Single Target. Roll 1 Chance die to Paralyze the Target.
Name: Thunderbolt
Power: 3
Target: Foe
Type: Electric
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