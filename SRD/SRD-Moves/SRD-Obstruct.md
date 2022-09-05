---
Accuracy1: Dexterity
Accuracy2: Intimidate
Damage1: ''
Damage2: ''
Description: In a reckless action, the user charges against the foe to stop its momentum
  and block its incoming attack. Being so close allows the user to reach for weak
  spots.
DmgType: Support
Effect: Priority 4. Shield Move. * If the Foe used a Non-Ranged Physical Move against
  the user, Reduce the Foes Defense by 2.
Name: Obstruct
Power: 0
Target: User
Type: Dark
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