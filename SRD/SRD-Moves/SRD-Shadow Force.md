---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Charge: true
  DestroyShield: true
  Lethal: true
Damage1: Strength
Damage2: ''
Description: The Pokemon disappears into a dark dimension to strike its foe at the
  next opportunity. The blow will hurt the target not on their body but directly on
  their soul.
DmgType: Physical
Effect: Lethal. Charge Move. While charging this Move, other Move will not affect
  the user. If the Target made a Shielding Action, the shield is destroyed and won't
  have any effect. Damage dealt by this Move cannot be healed for 24 hrs
Name: Shadow Force
Power: 5
Target: Foe
Type: Ghost
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