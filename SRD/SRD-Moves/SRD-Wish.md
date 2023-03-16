---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon makes a wish with all its might and somehow it becomes true.
DmgType: Support
Effect: Basic Heal. If successful spend 1 Will point to activate. The move has its
  effect at the beginning of the next round.
Name: Wish
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