---
Accuracy1: Dexterity
Accuracy2: BRAWL
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: Missing happiness
Description: A move that relies on how badly a Pokemon has been treated to make it
  vicious and uncaring.
Effect: Add +1 Dice to the Damage Roll for every missing point of Happiness on the
  User.
Name: Frustration
Power: 0
Target: Foe
Type: Normal
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