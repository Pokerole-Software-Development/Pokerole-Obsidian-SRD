---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: -2
    Stats:
    - Special
Attributes:
  AccuracyReduction: 1
  Lethal: true
Damage1: Special
Damage2: ''
Description: A light beam pierces the battlefield, it deals devastating damage but
  leaves newly grown flowers instead of scorched earth. The user is left feeling very
  tired.
DmgType: Special
Effect: Lethal. Reduce User's Special by 2. -1 Accuracy.
Name: Fleur Cannon
Power: 6
Target: Foe
Type: Fairy
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