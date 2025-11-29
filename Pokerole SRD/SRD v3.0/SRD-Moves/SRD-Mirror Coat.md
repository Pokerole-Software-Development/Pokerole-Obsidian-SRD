---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
  LateReaction: '5'
Category: Support
Damage1: Varies
Damage2: ''
Description: The user gathers the harmful energies around themselves and bounces them
  back to their source.
Effect: Single Target. Late Reaction 5. Can only be used if Target's last Move on
  User was a Special Move. For damage, roll dice equal to Target's last damage pool
  rolled against the User plus 2. Ignore Defenses.
Name: Mirror Coat
Power: 0
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