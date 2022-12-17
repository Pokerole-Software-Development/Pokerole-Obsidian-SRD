---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Burn
Attributes:
  AccuracyReduction: 1
Damage1: Special
Damage2: ''
Description: The user breathes a giant wave of incandescent air that might set fire
  to whatever it touches.
DmgType: Special
Effect: Target all foes in Range. Roll 1 Chance Dice to Burn those affected. -1 Accuracy.
Name: Heat Wave
Power: 3
Target: All Foes
Type: Fire
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