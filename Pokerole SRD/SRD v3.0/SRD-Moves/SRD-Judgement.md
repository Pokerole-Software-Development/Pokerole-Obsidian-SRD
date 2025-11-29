---
Accuracy1: Insight
Accuracy2: Intimidate
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: Sooner or later, everyone gets what they deserve.
Effect: Single Target. Unique. Ignore Defenses. This Move's Type, Power and extra
  Added Effects are decided by Storyteller. If something would prevent this Move from
  dealing Damage, ignore it. This Move can't be Clashed.
Name: Judgement
Power: 0
Target: Foe
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