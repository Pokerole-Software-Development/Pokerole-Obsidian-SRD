---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects: {}
Attributes:
  DestroyShield: true
  ResetTerrain: true
Damage1: ''
Damage2: ''
Description: A strong current of wind that blows away any fog and even invisible barriers.
DmgType: Support
Effect: Remove all Barriers (ie. Light Screen, Reflect), Entry Hazards (Toxic Spikes,
  Stealth Rock, etc.), and Terrains (Misty Terrain, Electric Terrain, etc.) from the
  battlefield.
Name: Defog
Power: 0
Target: Battlefield
Type: Flying
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