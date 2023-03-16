---
Accuracy1: Tough
Accuracy2: Nature
AddedEffects: {}
Attributes:
  HighCritical: true
  PhysicalRanged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user calls upon her swarm and heeds them to charge against you. No
  matter where you run, they will surround you. Hope you are not allergic to bees.
Effect: High Critical. Ranged.
Name: Attack Order
Power: 3
Target: Foe
Type: Bug
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