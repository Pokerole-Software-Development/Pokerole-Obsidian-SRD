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
Description: The user absorbs the vital energy of the foe.
DmgType: Special
Effect: The user restores HP equal to half the damage dealt rounded down.
Name: Absorb
Power: 1
Target: Foe
Type: Grass
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