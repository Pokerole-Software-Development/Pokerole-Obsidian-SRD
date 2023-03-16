---
Accuracy1: Insight
Accuracy2: Stealth
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  BlockDamagePool: 0
Category: Support
Damage1: ''
Damage2: ''
Description: The User quietly releases a web on the field. All foes will be trapped.
Effect: Blocks.
Name: Spider Web
Power: 0
Target: Battlefield
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