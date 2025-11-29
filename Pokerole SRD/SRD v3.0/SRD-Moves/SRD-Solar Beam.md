---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Charge: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon gathers sunlight but instead of being absorbed it is\
  \ sot as a devastating beam of light instead."
Effect: Single Target. Charge Move. If Sunny Weather is active, you skip this Move's
  Charge action. If performed under Rain, Sandstorm or Hail/Snowy Weather, this Move
  takes two actions to Charge.
Name: Solar Beam
Power: 6
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