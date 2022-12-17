---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Confuse
Attributes:
  AccuracyReduction: 3
  FistBased: true
Damage1: Strength
Damage2: ''
Description: A punch that hits a small pressure point. It leavers the foe disoriented.
DmgType: Physical
Effect: Fist Based. Confuse the foe. -3 Accuracy.
Name: Dynamic Punch
Power: 4
Target: Foe
Type: Fighting
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