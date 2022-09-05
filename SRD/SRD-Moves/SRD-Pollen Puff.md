---
Accuracy1: Special
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: The Pokemon creates a puff of pollen that explodes on the foe's face
  and gives them a terrible allergy. When consumed these puffs are sweet and very
  nutritious.
DmgType: Special
Effect: When this move is used against an ally it will heal 1 HP instead of dealing
  damage.
Name: Pollen Puff
Power: 3
Target: Foe
Type: Bug
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