---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects:
  Heal:
    Target: Targets
    Type: Basic
    WillPointCost: 1
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon drinks a glass of its own milk. The rich taste and nutrients
  revitalize it.
DmgType: Support
Effect: Basic Heal. If successful, spend 1 Will point to activate.
Name: Milk Drink
Power: 0
Target: User
Type: Normal
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