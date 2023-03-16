---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  FixedDamage:
    Target: Targets
    Type: OneHitKO
Attributes:
  AccuracyReduction: 5
  PhysicalRanged: true
Category: Physical
Damage1: ''
Damage2: ''
Description: The user tears the ground apart in a monstrous display of force. If the
  foe falls through the fissure it might need a rescue team to get it out.
Effect: Ranged. Deal damage to the Target equal to their remaining HP plus 1 lethal
  damage. -5 Accuracy.
Name: Fissure
Power: 0
Target: Foe
Type: Ground
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