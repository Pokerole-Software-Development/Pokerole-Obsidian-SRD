---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Duration: wholeScene
  HighCritical: true
  Lethal: true
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: With a flicker of its claws, Palkia defragments the space around its
  foe. Those who survive rarely do preserve their original shape much less move or
  fuction as they should.
Effect: Single Target. High Critical. Lethal. Unique. If successful, reduce 5 Success
  from all Accuracy rolls of the Target. Whole scene duration.
Name: Spacial Rend
Power: 4
Target: Foe
Type: Dragon
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