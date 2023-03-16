---
Accuracy1: Dexterity
Accuracy2: Perform
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon waves its hands with rhythm. The energy around follows the
  cadence and manifests with an impressive attack.
Effect: Roll a dice to determine this move's power. The appearance and Type of this
  move are decided by the Storyteller.
Name: Metronome
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