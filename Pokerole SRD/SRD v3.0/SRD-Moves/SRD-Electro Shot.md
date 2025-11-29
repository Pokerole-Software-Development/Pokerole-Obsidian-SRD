---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Charge: true
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user stands as tall as possible, waiting for a lightning to strike.
  Then re-directs the lightning directly towards the foe; recharging themselves in
  the process.
Effect: Single Target. Lethal. Charge Move. If Rain Weather is active, you skip this
  Move's Charge acton. Increase the User's Special Score by 1.
Name: Electro Shot
Power: 6
Target: Foe
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