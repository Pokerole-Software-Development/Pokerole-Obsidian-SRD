---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  SoundBased: true
Damage1: Special
Damage2: ''
Description: The Pokemon shouts and screams and squaks so hard the noise really hurts
  the ears. Nobody could get a full night of sleep with all that ruckus.
DmgType: Special
Effect: For the rest of the Round, no Pokemon can fall asleep. If a Pokemon was asleep
  it wakes up. Sound Based Move.
Name: Uproar
Power: 3
Target: Random Foe
Type: Normal
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`