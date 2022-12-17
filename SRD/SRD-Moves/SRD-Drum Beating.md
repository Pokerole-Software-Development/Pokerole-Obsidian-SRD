---
Accuracy1: Dexterity
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: Target
    Stages: 1
    Stats:
    - Dexterity
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The Pokemon has a perfectly good drum and you'd think it would use it.
  But it doesn't. It uses it's foe.
DmgType: Physical
Effect: Reduce the Foe's Dexterity
Name: Drum Beating
Power: 3
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