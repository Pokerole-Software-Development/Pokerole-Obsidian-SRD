---
Accuracy1: SPECIAL
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The user focuses the sunlight it has absorbed into a powerful and devastating
  beam of light.
DmgType: SPECIAL
Effect: Charge Move. If there is a Sunny Weather, you skip this Move's Charge action.
  If performed under Rain, Sandstorm, or Hail Weather, this Move takes two actions
  to Charge.
Name: Solar Beam
Power: 5
Target: Foe
Type: Grass
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