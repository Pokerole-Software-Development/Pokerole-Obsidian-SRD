---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes:
  UserFaints: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The last words of this Pok\xE9mon imprint their grudge and anger over\
  \ their foe. Depleting the foe of their will to carry on in this world."
Effect: Single Target. The User Faints. Reduce the Target's Will to 0 points and reset
  any effect it got from spending them. Roll Target's Loyalty at the end of the round,
  increase difficulty by 1 each round. Failing this roll faints the Target.
Name: Grudge
Power: 0
Target: Foe
Type: Ghost
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