---
Accuracy1: Insight
Accuracy2: Brawl/Channel
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
  LateReaction: '5'
Category: Physical
Damage1: Varies
Damage2: ''
Description: Those who live by the sword will die by the sword, or, in this case,
  by an explosion.
Effect: Single Target. Late Reaction 5. Can only be used if Target's last Move on
  User was a Physical or Special Move. Roll dice equal to Target's last damage pool
  rolled against the User plus 2 Dice. Ignore Defenses.
Name: Metal Burst
Power: 0
Target: Foe
Type: Steel
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