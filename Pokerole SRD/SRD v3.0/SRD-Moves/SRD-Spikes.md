---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes:
  EntryHazard: true
Category: Support
Damage1: ''
Damage2: ''
Description: "Sharp and pointy spikes are scattered around the field, if you don\u2019\
  t watch your step the spikes will dig on your feet."
Effect: Target Foe's Side of the Field. Entry Hazard. Pokemon entering the battle
  Receive 1 Typeless Damage. This effect does not stack. Pokemon with immunity to
  Ground-Type Moves are not affected.
Name: Spikes
Power: 0
Target: Foe's Battlefield
Type: Ground
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