---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  FixedDamage:
    BasedOn: Hp
    Percentage: 1
Attributes:
  AccuracyReduction: 5
  PhysicalRanged: true
Damage1: ''
Damage2: ''
Description: The user tears the ground apart in a monstrous display of force. If the
  foe falls through the fissure it might need a rescue team to get it out.
DmgType: Physical
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

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`