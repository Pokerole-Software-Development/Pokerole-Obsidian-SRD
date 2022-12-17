---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Paralyze
Attributes:
  Recoil: true
Damage1: Strength
Damage2: ''
Description: The user surrounds itself with big bolts of electricity, then it crashes
  against the foe.
DmgType: Physical
Effect: Recoil. Roll 1 Chance Dice to Paralyze the Foe.
Name: Volt Tackle
Power: 5
Target: Foe
Type: Electric
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