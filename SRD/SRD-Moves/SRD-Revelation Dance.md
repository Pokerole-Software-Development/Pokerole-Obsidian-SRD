---
Accuracy1: Dexterity
Accuracy2: Perform
AddedEffects: {}
Attributes: {}
Damage1: Special
Damage2: ''
Description: The Pokemon performa a dance. The dance's energy influences the Type
  of this Move.
DmgType: Special
Effect: This Move's type will always match the User's first Type.
Name: Revelation Dance
Power: 3
Target: Foe
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