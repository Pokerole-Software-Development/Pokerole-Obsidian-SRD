---
Accuracy1: Insight
Accuracy2: Perform
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: Varies
Damage2: ''
Description: "The Pok\xE9mon waves their hands following a specific rythm, the energy\
  \ around follows the cadence and manifests as a Move at random."
Effect: Single Target. Copy Move. Roll a die to determine Physical or Special category,
  roll a die to determine this Move's Power. The appearance, Type and added effects
  of this Move becomes the same of a Physical or Special Move of the same Power at
  Storyteller's Discretion.
Name: Metronome
Power: 0
Target: Foe
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