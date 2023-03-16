---
Accuracy1: Will
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user calls the forest to lay a curse upon the target, making it grow
  vines and vegetation around its whole body. The curse will not be easily lifted
  without a medium's help.
Effect: Add the Grass Type to the Target's Type (ie. Nidoran will now be Poison/Grass
  Heracross will now be Bug/Fight/Grass). If the Pokemon already has a third type
  attached then replace it.
Name: Forest's Curse
Power: 0
Target: Foe
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