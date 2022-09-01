---
Accuracy1: STRENGTH
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The user rises above the clouds and then comes crashing down against
  its foe in an instant. The strike is brutal for both.
DmgType: PHYSICAL
Effect: Lethal. Reduce the user's Defense and Sp. Defense.
Name: Dragon Ascent
Power: 5
Target: Foe
Type: Flying
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