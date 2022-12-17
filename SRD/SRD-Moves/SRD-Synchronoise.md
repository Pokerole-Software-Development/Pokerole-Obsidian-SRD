---
Accuracy1: Special
Accuracy2: Perform
AddedEffects: {}
Attributes:
  SoundBased: true
Damage1: Special
Damage2: ''
Description: The user vibrates with any particular energy Type he chooses. All nearby
  creatures and objects of that Type are hurt.
DmgType: Special
Effect: Sound Based. Choose a Type (Fire, Poison, Steel, etc.) this move only affects
  those with that Type.
Name: Synchronoise
Power: 5
Target: Area
Type: Psychic
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