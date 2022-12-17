---
Accuracy1: Dexterity
Accuracy2: Perform
AddedEffects: {}
Attributes:
  SoundBased: true
Damage1: Special
Damage2: ''
Description: The Pokemon uses its own body as an amplifier for the energizing sounds
  it produces.
DmgType: Special
Effect: All Foes in Range. Sound Based.
Name: Overdrive
Power: 3
Target: All Foes
Type: Electric
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