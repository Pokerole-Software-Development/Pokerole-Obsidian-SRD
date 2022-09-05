---
Accuracy1: Special
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: Foes are drenched in an odd poisonous liquid that targets their weakened
  immune systems.
DmgType: Support
Effect: If an affected foe is poisoned or becomes poisoned in the same Round you used
  this Move then Reduce its Strength, Special, and Dexterity.
Name: Venom Drench
Power: 0
Target: All Foes
Type: Poison
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