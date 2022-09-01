---
Accuracy1: INSIGHT
Accuracy2: INTIMIDATE
Damage1: SPECIAL
Damage2: ''
Description: Eventually, everyone gets what they deserve.
DmgType: SPECIAL
Effect: Ignore Defenses. This Move is considered to be any Type the user wants. If
  something would prevent this Move from dealing Damage, ignore it. This Move can't
  be Clashed. This Move's Power and extra Added Effects are decided by the Storyteller.
Name: Judgment
Power: 0
Target: Foe
Type: Normal
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`