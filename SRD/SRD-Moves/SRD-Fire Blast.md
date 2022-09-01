---
Accuracy1: SPECIAL
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The Pokemon shoots a giant fireball that explodes on contact with the
  foe, blasting fire in all directions.
DmgType: SPECIAL
Effect: Lethal. Roll 3 Chance Dice to apply Burn 3 to the foe. -2 Accuracy.
Name: Fire Blast
Power: 5
Target: Foe
Type: Fire
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`