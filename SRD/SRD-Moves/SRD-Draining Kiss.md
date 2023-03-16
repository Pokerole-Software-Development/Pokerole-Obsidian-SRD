---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Heal:
    Percentage: 0.5
    Target: User
    Type: Leech
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user sends a kiss with a flirty intention, the foe catches the kiss
  but it ends up draining the target's energy.
Effect: The User restores HP equal to half the damage dealt, rounded down.
Name: Draining Kiss
Power: 2
Target: Foe
Type: Fairy
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