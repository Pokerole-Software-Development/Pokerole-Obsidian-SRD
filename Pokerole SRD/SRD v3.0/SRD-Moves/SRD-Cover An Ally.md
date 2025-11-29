---
Accuracy1: Will
Accuracy2: ''
AddedEffects: {}
Attributes:
  Priority: 1
Category: Support
Damage1: ''
Damage2: ''
Description: Use your body as a shield to protect your friends! Not even 100 Spearrows
  will go through you!
Effect: "Target One Ally. Priority 1. The User will become the Target for incoming\
  \ attacks towards the Target. This Cover lasts until the User's Next Turn or until\
  \ the Target uses a Non-Ranged Physical Move. Pok\xE9mon with Loyalty 2 or less\
  \ won't use this Maneuver."
Name: Cover An Ally
Power: 0
Target: One Ally
Type: Typeless
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