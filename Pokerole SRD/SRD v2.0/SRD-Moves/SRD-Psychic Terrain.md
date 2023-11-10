---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  TerrainEffect: PsychicTerrain
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The arena becomes radiated by psychic waves. Everyone begins to think
  slowly due to the buzz in their heads, making all tasks take more time.
Effect: For the next 4 Rounds, all Psychic Attacks will deal 1 Extra Dice of Damage.
  No Pokemon on the ground can use moves with increased Priority.
Name: Psychic Terrain
Power: 0
Target: Battlefield
Type: Psychic
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