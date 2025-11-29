---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  TerrainEffect: MistyTerrain
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The battlefield is shrouded by a pink mist that feels protective and
  soothing. This mist is able to render even the fiercest beasts into calm.
Effect: Target Battlefield. All Status Ailments and Conditions are cured and no more
  can be inflicted. Physical & Special Dragon-Type Moves have Power 0. Duration 4
  Rounds.
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