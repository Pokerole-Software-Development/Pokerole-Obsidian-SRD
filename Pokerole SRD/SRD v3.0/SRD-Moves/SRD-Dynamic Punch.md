---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Confuse
Attributes:
  AccuracyReduction: -3
  FistMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: A punch to a vital pressure point on the foe to disrupt their sense of
  balance
Effect: Single Target. Low Accuracy 3. Fist Move. Confuse the Target.
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

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`