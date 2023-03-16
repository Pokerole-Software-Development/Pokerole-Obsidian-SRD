---
Accuracy1: Dexterity
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: User
    ChanceDice: 5
    Stages: 1
    Stats:
    - Special
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user cloaks itself in flames and shoots them while dancing gracefully.
Effect: Roll 5 Chance Dice to Increase the User's Special.
Name: Fiery Dance
Power: 3
Target: Foe
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