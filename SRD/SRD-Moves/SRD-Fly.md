---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: User
    Type: Fly
Attributes:
  Charge: true
Damage1: Strength
Damage2: ''
Description: The user flies up high in one action, then drops and strikes in the next
  one. The Pokemon can fly for extremely long periods of time without getting tired.
DmgType: Physical
Effect: Charge Move. While charging this move the User will be out of range, with
  the exception of the attacks Hurricane and Thunder.
Name: Fly
Power: 3
Target: Foe
Type: Flying
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`