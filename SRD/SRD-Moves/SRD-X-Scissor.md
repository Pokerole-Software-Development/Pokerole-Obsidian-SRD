---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The Pokemon uses its scythes or claws as if they were a pair of scissors
  to cut through the foe.
DmgType: Physical
Effect: '-'
Name: X-Scissor
Power: 3
Target: Foe
Type: Bug
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