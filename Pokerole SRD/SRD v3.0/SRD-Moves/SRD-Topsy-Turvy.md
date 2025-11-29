---
Accuracy1: Clever
Accuracy2: Alert/Intimidate
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "Though clever manipulation the Pok\xE9mon switches their foe\u2019s\
  \ morality compass. Bad things become good and bad things become bad."
Effect: Single Target. Increased Attributes on the Target become Reductions instead
  and vice versa.
Name: Topsy-Turvy
Power: 0
Target: Foe
Type: Dark
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