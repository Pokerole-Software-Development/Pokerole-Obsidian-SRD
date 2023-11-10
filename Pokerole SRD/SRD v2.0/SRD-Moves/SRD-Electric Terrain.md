---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user electrifies the terrain, making it impossible to get a good
  night's sleep on it.
Effect: For the Next 4 Rounds all Electric Attacks will deal 1 Extra Dice of Damage.
  Anyone on the ground will be cured from "Sleep" Status.
Name: Electric Terrain
Power: 0
Target: Battlefield
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