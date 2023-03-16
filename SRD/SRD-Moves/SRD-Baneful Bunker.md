---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects: {}
Attributes:
  Priority: 4
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user encloses itself inside its sturdy shell, which is covered by
  poisonous barbs. If a barb pinches the foe's skin the wound will start to fester.
Effect: Priority 4. Shield. If the foe attacked using a Physical Move, it is now Poisoned.
  Reduce 3 Dice from the Foe's Damage Pool.
Name: Baneful Bunker
Power: 0
Target: User
Type: Poison
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