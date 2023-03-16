---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Heal:
    Percentage: 0.5
    Target: User
    Type: Leech
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The user attacks a vital spot and sucks away the vitality of its foe.
DmgType: Physical
Effect: The user restores HP equal to half the damage dealt rounded down.
Name: Leech Life
Power: 3
Target: Foe
Type: Bug
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