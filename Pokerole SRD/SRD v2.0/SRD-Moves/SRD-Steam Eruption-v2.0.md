---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Burn2
Attributes:
  AccuracyReduction: 1
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: In less than a second, the sound of steam boiling over a raging engine
  thunders through the ears of the foe before it is shot through the sky by a scalding
  geyser.
Effect: Lethal. Roll 3 Chance Dice to Apply Burn 2 to those affected. -1 Accuracy.
Name: Steam Eruption
Power: 4
Target: Foe
Type: Water
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