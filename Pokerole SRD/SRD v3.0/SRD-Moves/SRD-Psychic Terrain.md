---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  TerrainEffect: PsychicTerrain
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: The arena becomes radiated by psychic waves. Everyone feels their mind
  slog due to the buzz in their heads, making all tasks take longer than they should.
Effect: Target Battlefield. Add 1 Extra Damage Dice to all Physical & Special Psychic-Type
  Moves. Pokemon without immunity to Ground can't use Moves with Reaction or Late
  Reaction. Duration 4 Rounds.
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