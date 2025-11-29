---
Accuracy1: Dexterity
Accuracy2: Channel/Nature
AddedEffects: {}
Attributes:
  CutterMove: true
  HighCritical: true
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The user sends out a barrage of sharp razor-like leaves. \u201CDeath\
  \ by a thousand cuts\u201D would be the best depiction."
Effect: Target All Foes in Range. Cutter Move. Ranged. High Critical.
Name: Razor Leaf
Power: 2
Target: All Foes
Type: Grass
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