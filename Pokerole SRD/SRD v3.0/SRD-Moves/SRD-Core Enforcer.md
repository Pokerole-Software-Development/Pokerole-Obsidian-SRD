---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Duration: wholeScene
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: Zygarde shoots a beam that fractures the target to its core, rendering
  it unable to sustain even their own essence.
Effect: Single Target. If the User has already received Damage from the Target this
  Round, Remove the Target's Ability for the rest of the scene. This effect does not
  end by switching out the affected Pokemon. Unique Abilities are not affected by
  this effect.
Name: Core Enforcer
Power: 4
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