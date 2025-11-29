---
Accuracy1: Special
Accuracy2: Perform/Nature
AddedEffects:
  TerrainEffect: Rain
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon performs a peculiar dance in the middle of the field,\
  \ everyone thinks it silly until the first thunder rumbles."
Effect: Target Battlefield. Activate Rain Weather. Duration 4 Rounds.
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

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`