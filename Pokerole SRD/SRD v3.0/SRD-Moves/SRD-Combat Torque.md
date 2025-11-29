---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: After shaking and beating their target up, the user will attempt to immovilize
  them.
Effect: Single Target. Lethal. Ranged. Roll 3 Chance dice to Paralyze the Target.
Name: Combat Torque
Power: 4
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