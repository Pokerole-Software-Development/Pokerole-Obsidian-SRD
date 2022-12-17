---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  NeverFail: true
  PhysicalRanged: true
Damage1: Strength
Damage2: ''
Description: The Pokemon hurls a metal bomb that is attracted to the target like a
  magnet. The moment it touches the foe, it will explode.
DmgType: Physical
Effect: Ranged. Never Fail.
Name: Magnet Bomb
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