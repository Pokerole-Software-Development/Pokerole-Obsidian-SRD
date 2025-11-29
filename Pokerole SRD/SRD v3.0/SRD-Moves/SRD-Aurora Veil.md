---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: AuroraVeil
Attributes:
  Duration: 4
  ForceField:
    DamageReduction: 1
    DamageType: all
Category: Support
Damage1: ''
Damage2: ''
Description: If the weather is cold enough, beautiful aurora lights will cover half
  of the battlefield, deflecting attacks.
Effect: Target User's Side of the Field. Force Field against Physical & Special Damage.
  This move will fail if not performed under Hail/Snowy Weather. Duration 4 Rounds,
  even if Hail or Snow Weather is over.
Name: Aurora Veil
Power: 0
Target: Ally's Battlefield
Type: Ice
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