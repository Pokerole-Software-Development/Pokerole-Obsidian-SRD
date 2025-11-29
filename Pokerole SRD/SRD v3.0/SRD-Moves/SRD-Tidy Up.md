---
Accuracy1: Cute
Accuracy2: Etiquette
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user coordinates a quick and efficient way to clean up the whole
  place. No things scattered on the floor, no toys out of the toybox. Perfect for
  when visits come over.
Effect: Target Battlefield. Remove all active Substitute/Shed Tail Decoys and Entry
  Hazards (ie Sticky Web, Spikes, Toxic Spikes, etc.). Increase the User's Strength
  and Dexterity by 1.
Name: Tidy Up
Power: 0
Target: Battlefield
Type: Normal
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