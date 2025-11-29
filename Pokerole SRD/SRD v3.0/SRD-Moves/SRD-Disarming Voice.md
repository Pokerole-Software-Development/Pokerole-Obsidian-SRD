---
Accuracy1: Insight
Accuracy2: Charm/Perform
AddedEffects: {}
Attributes:
  NeverMiss: true
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: With a charming but manipulative cry, the user deals emotional damage
  to their opponent by making them feel guilty.
Effect: Target All Foes in Range. Sound Move. Never Miss.
Name: Disarming Voice
Power: 2
Target: All Foes
Type: Fairy
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