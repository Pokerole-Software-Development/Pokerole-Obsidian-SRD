---
Accuracy1: Strength
Accuracy2: Brawl
Damage1: Strength
Damage2: ''
Description: The user focuses on exploding its body, the explosion deals a massive
  wave of damage. A very dangerous move.
DmgType: Physical
Effect: After the damage is dealt the User faints. Lethal.
Name: Explosion
Power: 10
Target: Area
Type: Normal
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