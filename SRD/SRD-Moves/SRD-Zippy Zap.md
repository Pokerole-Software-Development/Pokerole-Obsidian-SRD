---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AlwaysCrit: true
  Priority: 2
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user zips and zaps from one place to another to strike the foe moving
  so fast it appears to be teleporting, leaving almost no time to react.
Effect: Priority 2. This Move is always a Critical Hit and gets the proper Bonus for
  it. If the user of this Move is at its Final Stage of Evolution, this move fails.
Name: Zippy Zap
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