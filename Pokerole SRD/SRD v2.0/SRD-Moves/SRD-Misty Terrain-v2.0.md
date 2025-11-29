---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  TerrainEffect: MistyTerrain
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user surrounds the battlefield with a mystical mist that feels protective.
  Mythical Pokemon find something eerie about it.
Effect: Creatures standing on the battlefield won't be affected by Status Ailments.
  Dragon Type attacks won't add their Power to the Damage Pool. Lasts 4 Rounds.
Name: Misty Terrain
Power: 0
Target: Battlefield
Type: Fairy
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