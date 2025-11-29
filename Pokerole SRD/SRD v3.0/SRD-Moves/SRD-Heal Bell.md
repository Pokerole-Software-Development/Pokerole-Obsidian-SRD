---
Accuracy1: Special
Accuracy2: Perform
AddedEffects:
  AilmentHeal:
  - All
Attributes:
  SoundMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The soothing chime of a magical bell cleanses all impurities.
Effect: Target User and Allies in Range. Sound Move. Cure any Status Ailment on the
  Targets.
Name: Heal Bell
Power: 0
Target: All Allies
Type: Normal
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