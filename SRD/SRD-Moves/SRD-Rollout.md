---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  SuccessiveActions: true
Damage1: Strength
Damage2: ''
Description: The user curls up into a ball and starts rolling towards its foe, trampling
  everything in its way.
DmgType: Physical
Effect: Successive Actions. Add 1 Extra Dice to the Damage Roll of the last Rollout
  hit the user performs. If the Pokemon used Defense Curl this Round, add 1 Extra
  Dice to the Damage Roll of every hit. -1 Accuracy.
Name: Rollout
Power: 1
Target: Foe
Type: Rock
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`