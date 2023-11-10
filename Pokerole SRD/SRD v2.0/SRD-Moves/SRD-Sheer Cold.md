---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  FixedDamage:
    Target: Targets
    Type: OneHitKO
Attributes:
  AccuracyReduction: 5
  Lethal: true
Category: Special
Damage1: ''
Damage2: ''
Description: The user freezes the foe from the inside out. Victims of this attack
  will need urgent medical attention.
Effect: Deal damage to the Target equal to its remaining HP plus 1 Lethal Damage.
  -5 Accuracy.
Name: Sheer Cold
Power: 0
Target: Foe
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