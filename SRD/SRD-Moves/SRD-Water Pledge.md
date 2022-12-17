---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Target
    Rounds: 4
    Type: WaterPledge
  TerrainEffect: WaterPledge
Attributes: {}
Damage1: Special
Damage2: ''
Description: The Pokemon chants to invoke the power of Water. Moisture in the air
  bends the light to create an inspiring rainbow. Everyone in the field is sure to
  give its best.
DmgType: Special
Effect: Creates a rainbow that adds 2 Dice to all Chance Dice rolls. This effect lasts
  4 turns.
Name: Water Pledge
Power: 2
Target: Battlefield and Area
Type: Water
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