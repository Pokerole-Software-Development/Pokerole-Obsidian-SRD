---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  TerrainEffect: Rain
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user performs a curious mystic dance that summons a heavy rainfall.
DmgType: Support
Effect: Rain Weather is activated for the next 4 Rounds.
Name: Rain Dance
Power: 0
Target: Battlefield
Type: Water
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