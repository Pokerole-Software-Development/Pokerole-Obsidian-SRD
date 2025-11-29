---
Accuracy1: SameasCopiedMove
Accuracy2: ''
AddedEffects: {}
Attributes:
  CopyMove: true
  Unique: true
Category: Support
Damage1: SameasCopiedMove
Damage2: ''
Description: The user is incredibly observant and has a talent for impersonations,
  no one will tell the difference!
Effect: Single Target. Copy Move. Unique Moves can't be copied. You may choose another
  Target(s) for the copied Move.
Name: Copycat
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