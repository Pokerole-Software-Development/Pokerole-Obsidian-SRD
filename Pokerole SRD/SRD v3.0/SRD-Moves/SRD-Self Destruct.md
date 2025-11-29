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
Description: "It\u2019s not about winning or losing, some pok\xE9mon just want to\
  \ see the world burn."
Effect: Area Move. Lethal. Ranged. The User faints.
Name: Self Destruct
Power: 8
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