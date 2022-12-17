---
Accuracy1: Clever
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: User
    Type: ChangedAbility
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user mimics the target and takes on the most basic features from
  that character.
DmgType: Support
Effect: Copy the target's Ability. The abilities Flower Gift, Illusion, Imposter,
  Stance Change, Wonder Guard, and Plot Device cannot be copied.
Name: Role Play
Power: 0
Target: Foe
Type: Psychic
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