---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  FixedDamage:
    Target: Targets
    Type: Absolute
    Value: 2
Attributes: {}
Damage1: ''
Damage2: ''
Description: A dual colored flame that always leaves the same burn marks on everything
  it touches.
DmgType: Special
Effect: This moves always inflicts 2 damage.
Name: Dragon Rage
Power: 0
Target: Foe
Type: Dragon
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