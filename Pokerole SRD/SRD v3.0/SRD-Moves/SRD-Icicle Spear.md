---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  PhysicalRanged: true
  Ranged: true
  SuccessiveActions: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: A barrage of icicles shot against the target. They are small but sharp
  and pointy
Effect: Single Target. Ranged. Successive Actions.
Name: Icicle Spear
Power: 1
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