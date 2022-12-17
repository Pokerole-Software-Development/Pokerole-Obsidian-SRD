---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The Pokemon throws a tantrum all over the place, it becomes worse if
  something has frustrated it earlier.
DmgType: Physical
Effect: Add 2 Extra Dice to the Damage Pool of this move is the User failed the Accuracy
  Roll of the last Move it performed.
Name: Stomping Tantrum
Power: 3
Target: Foe
Type: Ground
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