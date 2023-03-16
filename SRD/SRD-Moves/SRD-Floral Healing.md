---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  Heal:
    Target: Targets
    Type: Basic
    WillPointCost: 1
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user creates a flower crown that heals and relaxes its wearer. Under
  the right conditions this move also creates a flower patch around its target.
Effect: Basic Heal. If performed over Grassy Terrain this move is a Complete Heal.
Name: Floral Healing
Power: 0
Target: One Ally
Type: Fairy
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`