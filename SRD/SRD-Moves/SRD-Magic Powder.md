---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    TargetType: Psychic
    Type: ChangedType
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon recites an enchantment and blows a cloud of pink dust on
  its Target. Afterwards, the target becomes especially good at guessing which card
  you got from a deck.
DmgType: Support
Effect: Change the target's Type to Psychic.
Name: Magic Powder
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