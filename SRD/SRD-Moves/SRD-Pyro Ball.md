---
Accuracy1: Strength
Accuracy2: Channel
Damage1: Strength
Damage2: ''
Description: The Pokemon lights a heavy stone on fire and kicks it while it's ablaze.
  The hit is pretty heavy already, the fire is just for showing off.
DmgType: Physical
Effect: Roll 1 Chance Dice to Apply Burn 2 to the Foe. -1 Accuracy.
Name: Pyro Ball
Power: 5
Target: Foe
Type: Fire
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