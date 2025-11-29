---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  Lethal: true
  MustRecharge: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon will make an incredible jump to the sky, then lunge towards\
  \ the foe at a staggering speed, crashing the ground upon impact. The user is left\
  \ very tired."
Effect: Single Target. Low Accuracy 1. Lethal. Must Recharge.
Name: Meteor Assault
Power: 6
Target: Foe
Type: Fighting
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