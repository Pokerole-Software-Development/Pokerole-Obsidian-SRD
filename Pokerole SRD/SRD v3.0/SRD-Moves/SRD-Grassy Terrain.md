---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  TerrainEffect: GrassyTerrain
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: A patch of grass grows in the area surrounding the user, through it nature
  grants her many blessings.
Effect: Target User's side of the field. Add 1 Extra Damage Dice to all Physical &
  Special Grass-Type Moves. Everyone on the User's side of the field heals 1 HP at
  the end of each Round. Spend 1 Will Point t activate. Duration 4 Rounds.
Name: Grassy Terrain
Power: 0
Target: Ally's Battlefield
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