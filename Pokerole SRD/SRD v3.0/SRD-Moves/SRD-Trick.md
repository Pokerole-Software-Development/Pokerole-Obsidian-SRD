---
Accuracy1: Clever
Accuracy2: Charm/Stealth
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The user controls its target\u2019s mind to make them do a simple non-hostile\
  \ action, such as walking or handing an item. Although some Pok\xE9mon use simple\
  \ sleigh of hand."
Effect: Single Target. The User and the Target switch their Held Item. If only one
  Pokemon is holding an Item, it gives it away.
Name: Trick
Power: 0
Target: Foe
Type: Psychic
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