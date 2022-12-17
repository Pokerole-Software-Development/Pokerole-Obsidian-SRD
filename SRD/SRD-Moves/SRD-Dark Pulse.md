---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Flinch
Attributes: {}
Damage1: Special
Damage2: ''
Description: The Pokemon sends a wave of dark feelings that affect those who are most
  vulnerable, hurting the foe and leaving it unable to act.
DmgType: Special
Effect: Targets random foe. Roll 2 Chance Dice to Flinch the foe.
Name: Dark Pulse
Power: 3
Target: Random Foe
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