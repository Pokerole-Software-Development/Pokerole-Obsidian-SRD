---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user shoots a pulse that absorbs the energy flowing in the area to
  devastate its foes.
Effect: Single Target. *Add 2 Extra Dice to the Damage Pool if there is a Terrain
  active in the Battlefield. Change this Move's Type to match that of a currently
  active Terrain (ie Electric Terrain, Grassy Terrain, etc.).
Name: Terrain Pulse
Power: 2
Target: Foe
Type: Normal
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