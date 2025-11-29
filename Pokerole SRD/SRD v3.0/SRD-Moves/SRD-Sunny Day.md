---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  TerrainEffect: Sunny
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon will call for the sun to shine brighter, increasing the\
  \ heat of the arena. This Move doesn\u2019t work at night, indoors, or underground/water."
Effect: Target Battlefield. Activate Sunny Weather. Duration 4 Rounds.
Name: Sunny Day
Power: 0
Target: Battlefield
Type: Fire
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