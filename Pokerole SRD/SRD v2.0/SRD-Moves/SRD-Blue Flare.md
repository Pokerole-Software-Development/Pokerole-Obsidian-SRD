---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Burn3
Attributes:
  AccuracyReduction: 2
Category: Special
Damage1: Special
Damage2: ''
Description: Reshiram surrounds itself with a giant blue flame that is unleashed with
  an earth shattering explosion. Receiving this attack directly might completely engulf
  you in fire.
Effect: Roll 2 Chance Dice to Apply Burn 3 to the foe. -2 Accuracy.
Name: Blue Flare
Power: 6
Target: Foe
Type: Fire
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