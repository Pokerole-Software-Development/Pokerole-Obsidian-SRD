---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  PhysicalRanged: true
  Ranged: true
  UserFaints: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Through a massive explosion the Pok\xE9mon destroys all they can before\
  \ fainting. Sometimes the only way to get out of a bad situation is in bits and\
  \ pieces."
Effect: Area Move. Ranged. Lethal. The User Faints.
Name: Explosion
Power: 10
Target: Area
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