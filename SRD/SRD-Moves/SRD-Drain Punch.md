---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Heal:
    Percentage: 0.5
    Type: Leech
Attributes:
  FistBased: true
Damage1: Strength
Damage2: ''
Description: The Pokemon strikes with a powerful punch. Through contact, it absorbs
  some vital energy.
DmgType: Physical
Effect: Fist Based. The user restore HP equal to half the damage dealt, rounded down.
Name: Drain Punch
Power: 3
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