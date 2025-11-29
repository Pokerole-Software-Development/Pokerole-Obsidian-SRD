---
Accuracy1: Insight
Accuracy2: Perform
AddedEffects: {}
Attributes:
  CopyMove: true
  Unique: true
Category: Support
Damage1: SameasCopiedMove
Damage2: ''
Description: "The Pok\xE9mon parrots the target cries and movements. In an almost\
  \ perfect impersonation that manages to copy its powers."
Effect: Single Target. Copy Move. Unique Moves can't be copied. You may choose another
  Target(s) for the copied Move.
Name: Mirror Move
Power: 0
Target: Foe
Type: Flying
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