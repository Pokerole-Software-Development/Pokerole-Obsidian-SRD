---
Accuracy1: Tough
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Torment
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user torments and enrages the foe, making it unable to keep using
  its strategy.
DmgType: Support
Effect: The target cannot use the same Moves it used during the last Round. Lasts
  4 Rounds.
Name: Torment
Power: 0
Target: Foe
Type: Dark
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