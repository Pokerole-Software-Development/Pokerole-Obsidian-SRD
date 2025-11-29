---
Accuracy1: Clever
Accuracy2: Stealth
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon uses a bit of sleigh of hand to switch their Held Item\
  \ with the target\u2019s, who don\u2019t even notice what happened."
Effect: Single Target. The User and the Target switch their Held Item. If only one
  Pokemon is holding an Item, it gives it away.
Name: Switcheroo
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