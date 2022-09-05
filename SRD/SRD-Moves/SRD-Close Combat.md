---
Accuracy1: Strength
Accuracy2: Brawl
Damage1: Strength
Damage2: ''
Description: The user attacks at a close distance to deal lots of damage. The foe
  is also close enough to attack.
DmgType: Physical
Effect: After dealing damage, Reduce the User's Defense and Sp. Defense.
Name: Close Combat
Power: 5
Target: Foe
Type: Fighting
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