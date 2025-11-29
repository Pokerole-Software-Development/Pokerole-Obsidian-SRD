---
Accuracy1: Insight
Accuracy2: Charm
AddedEffects: {}
Attributes:
  CopyMove: true
  Unique: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon sends a psychic command to a target, enabling the user\
  \ to mentally tell them what to do. If you see a Pok\xE9mon attacking their own\
  \ allies... this was it."
Effect: Single Target. Copy Move. Unique Moves can't be copied. You may choose another
  Target(s) for the copied Move.
Name: Instruct
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