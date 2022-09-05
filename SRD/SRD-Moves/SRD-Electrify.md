---
Accuracy1: Insight
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: The user hurls an electric projectile to the target, the foe is charged
  with electricity until it is released by the foe's next attack.
DmgType: Support
Effect: The Damage from the next attack made by the target will be Electric Type.
Name: Electrify
Power: 0
Target: Foe
Type: Electric
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