---
Accuracy1: Strength
Accuracy2: Brawl
Damage1: Strength
Damage2: ''
Description: The user will capture its foe in a crushing jaw grip. It won't let go
  no matter how much you try to seperate them. The only way it will release its victim
  is by fainting.
DmgType: Physical
Effect: Both User and Target are Blocked.
Name: Jaw Lock
Power: 3
Target: Foe
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