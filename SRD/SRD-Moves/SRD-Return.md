---
Accuracy1: Dexterity
Accuracy2: Brawl
Damage1: Strength
Damage2: Happiness
Description: If the Pokemon is treated with care and love, it will return that affection
  by giving all it's got in battle.
DmgType: Physical
Effect: Add 1 Dice to the Damage Roll for every point of Happiness on the User.
Name: Return
Power: 0
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