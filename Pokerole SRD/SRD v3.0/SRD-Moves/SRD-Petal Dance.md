---
Accuracy1: Special
Accuracy2: Perform/Nature
AddedEffects: {}
Attributes:
  Rampage: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon casts a huge cluster of petals to dance in the wind;\
  \ they let nature run its course, as the wind will choose who will take the devastating\
  \ blow."
Effect: Target Random Foe. Rampage.
Name: Petal Dance
Power: 5
Target: Random Foe
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