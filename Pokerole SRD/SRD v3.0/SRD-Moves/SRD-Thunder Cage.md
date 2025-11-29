---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Blocks: true
  Duration: 4
  OngoingDamage: true
Category: Special
Damage1: Special
Damage2: ''
Description: Several lightning spheres are placed in the battlefied as if they were
  a tesla coil. Shooting thunderbolts non-stop and blasting those unfortunate enough
  to be trapped in it.
Effect: Single Target. Blocks. Ongoing Damage. Duration 4 Rounds. Increase the Target's
  difficulty to Evade at Storyteller's discretion.
Name: Thunder Cage
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