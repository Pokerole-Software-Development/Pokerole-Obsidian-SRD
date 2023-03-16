---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: A powerful slap that makes even the laziest Pokemon be well awake.
Effect: If the Foe is sleeping, Add 2 Extra Dice to the Damage Pool. The foe Wakes
  up afterwards.
Name: Wake-Up Slap
Power: 2
Target: Foe
Type: Fighting
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