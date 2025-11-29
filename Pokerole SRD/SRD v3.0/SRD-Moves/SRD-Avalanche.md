---
Accuracy1: Strength
Accuracy2: Nature
AddedEffects: {}
Attributes:
  LateReaction: '4'
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user covers themselves with a heavy snow coat, if anything disturbs
  the snow, it will fall like a heavy avalanche.
Effect: Single Target. Late Reaction 4. *If the User received damage from the target
  during this Turn add 2 Extra Dice to the Damage Pool. *If Snowy Weather is active
  add 2 Extra Dice to the Damage Pool.
Name: Avalanche
Power: 2
Target: Foe
Type: Ice
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