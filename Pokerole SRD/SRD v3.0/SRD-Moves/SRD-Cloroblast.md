---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Recoil: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon concentrates all of the chlorophyll inside of its body\
  \ and then makes it explode. Targets are usually tinted green for days afterwards."
Effect: Single Target. Recoil.
Name: Cloroblast
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