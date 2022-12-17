---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Lethal: true
Damage1: Strength
Damage2: ''
Description: The Pokemon grips the foe and starts crushing it. Small targets are difficult
  to grasp but larger bodies will not be released until they break.
DmgType: Physical
Effect: Lethal. If the foe has a Base HP higher than 3, add 1 Die to the Damage pool
  for every exceeding point. Up to 9 Dice may be added this way
Name: Crush Grip
Power: 1
Target: Foe
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