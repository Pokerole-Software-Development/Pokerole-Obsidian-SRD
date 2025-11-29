---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  CutterMove: true
  HighCritical: true
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The User compacts water and shoots it as a pressurized jet. This jet
  is very sharp and can easily cut through solids.
Effect: Single Target. Ranged. High Critical. Cutter Move.
Name: Aqua Cutter
Power: 2
Target: Foe
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