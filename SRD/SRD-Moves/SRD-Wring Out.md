---
Accuracy1: Strength
Accuracy2: Brawl
Damage1: Strength
Damage2: ''
Description: The Pokemon literally squeezes the life out of its target. As life is
  fading, squeezing will be harder.
DmgType: Physical
Effect: Remove 1 Dice from the Damage Roll for every missing HP of the Target. Up
  to 4 dice may be removed this way.
Name: Wring Out
Power: 5
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