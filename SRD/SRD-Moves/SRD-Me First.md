---
Accuracy1: Dexterity
Accuracy2: Brawl
Damage1: ''
Damage2: ''
Description: The user anticipates the next attack so it can hit the target with an
  astounding speed.
DmgType: Support
Effect: Priority 1. The User copies and uses the Move the target was intending to
  use. It must be a damaging Move.
Name: Me First
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