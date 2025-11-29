---
Accuracy1: Dexterity/Insight
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Confuse
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon dances with wobbly movements and erratic spins. The spectators\
  \ don\u2019t know what to make of these modern choreographies."
Effect: Area Move. Confuse those affected.
Name: Teeter Dance
Power: 0
Target: Area
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