---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Priority: -4
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user builds up a lot of snow around itself. If anything disturbs
  the snow, it will fall on the attacker like an avalanche.
Effect: Low Priority 4. If the user received damage from the target this Round, Add
  2 Extra Dice to the Damage Pool.
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