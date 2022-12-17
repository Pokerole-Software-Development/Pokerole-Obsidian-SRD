---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  SoundBased: true
Damage1: Special
Damage2: ''
Description: The user creates an explosive sound that deafens everyone in the battlefield.
DmgType: Special
Effect: Sound Based.
Name: Boomburst
Power: 6
Target: Area
Type: Normal
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