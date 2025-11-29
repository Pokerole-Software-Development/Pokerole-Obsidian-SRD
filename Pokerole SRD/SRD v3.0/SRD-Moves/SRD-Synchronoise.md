---
Accuracy1: Special
Accuracy2: Channel/Perform
AddedEffects: {}
Attributes:
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: Each type of energy is contained by a thin layer of particles. With the
  right vibration frequency, that thin layer can be shattered like glass.
Effect: Area Move. Sound Move. Choose one Type (Fire, Poison, Steel, etc.). This move
  only affects those with that Type.
Name: Synchronoise
Power: 5
Target: Area
Type: Psychic
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