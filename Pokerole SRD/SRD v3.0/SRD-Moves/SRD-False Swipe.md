---
Accuracy1: Strength
Accuracy2: Perform
AddedEffects: {}
Attributes:
  CutterMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Through their most dramatic poses, the Pok\xE9mon pretends to slice\
  \ up the foe (the blood is fake)."
Effect: Single Target. Cutter Move. This Move's Damage can't make the Target go below
  1 HP.
Name: False Swipe
Power: 2
Target: Foe
Type: Normal
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