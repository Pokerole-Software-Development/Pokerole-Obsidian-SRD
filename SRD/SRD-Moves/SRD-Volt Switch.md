---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  SwitcherMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: The User quickly shoots an electic jolt, then switches places with an
  awaiting Pokemon partner at the speed of lightning.
Effect: The user switches out after dealing damage. The new Pokemon arrives ready
  to fight on the next Round. Switcher Move.
Name: Volt Switch
Power: 2
Target: Foe
Type: Electric
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