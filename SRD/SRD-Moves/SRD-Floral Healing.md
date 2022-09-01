---
Accuracy1: INSIGHT
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: The user creates a flower crown that heals and relaxes its wearer. Under
  the right conditions this move also creates a flower patch around its target.
DmgType: SUPPORT
Effect: Basic Heal. If performed over Grassy Terrain this move is a Complete Heal.
Name: Floral Healing
Power: 0
Target: One Ally
Type: Fairy
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