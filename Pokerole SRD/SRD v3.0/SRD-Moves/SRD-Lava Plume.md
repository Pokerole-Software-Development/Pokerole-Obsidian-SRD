---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Burn
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The floor is lava. The sky is lava. Everywhere is lava. Hundreds of lava
  bits start raining scattered around the field.
Effect: Area Move. Roll 3 Chance Dice to inflict 1st Degree Burn on those affected.
Name: Lava Plume
Power: 3
Target: Area
Type: Fire
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