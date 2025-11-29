---
Accuracy1: Will
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Spite
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user is believed to transport themselves to the land of dreams to
  torment their victims with vivid night terrors. The vicitms wake up with unexplainable
  injuries.
Effect: Single Target. Can only be used if the Target has the Sleep Condition. Deal
  1 Typeless Damage to the Target after every attempt to resist its Sleep Condition
  where it doesn't wake up.
Name: Nightmare
Power: 0
Target: Foe
Type: Ghost
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