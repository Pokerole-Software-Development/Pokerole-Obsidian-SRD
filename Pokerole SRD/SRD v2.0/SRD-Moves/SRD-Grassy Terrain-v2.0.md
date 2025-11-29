---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  TerrainEffect: GrassyTerrain
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon calls upon the healing power of nature to grow a patch of
  miraculous grass on its side of the battlefield.
Effect: If successful, spend 1 Will point to activate. Everyone in the user's side
  of the field heals 1 HP at the end of each round. Add 1 Extra Dice to the Damage
  Rolls of Grass Type Moves.
Name: Grassy Terrain
Power: 0
Target: Battlefield
Type: Grass
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