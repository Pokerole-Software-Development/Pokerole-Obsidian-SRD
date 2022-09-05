---
Accuracy1: Dexterity
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: The user dazes the foe with a beam of light. Those who have experienced
  it describe it as
DmgType: Special
Effect: Roll 3 Chance Dice to Confuse the foe. -2 Accuracy.
Name: Mirror Shot
Power: 2
Target: Foe
Type: Steel
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