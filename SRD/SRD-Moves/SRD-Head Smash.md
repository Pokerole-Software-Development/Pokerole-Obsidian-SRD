---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: 2
  Recoil: true
Damage1: Strength
Damage2: ''
Description: The user charges head first to attack the foe, the strike is devastating
  for both.
DmgType: Physical
Effect: Recoil. -2 Accuracy.
Name: Head Smash
Power: 6
Target: Foe
Type: Rock
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