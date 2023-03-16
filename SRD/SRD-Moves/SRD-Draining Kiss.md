---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Heal:
    Percentage: 0.5
    Target: User
    Type: Leech
Attributes: {}
Damage1: Special
Damage2: ''
Description: The user sends a kiss with a flirty intention, the foe catches the kiss
  but it ends up draining the target's energy.
DmgType: Special
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

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`