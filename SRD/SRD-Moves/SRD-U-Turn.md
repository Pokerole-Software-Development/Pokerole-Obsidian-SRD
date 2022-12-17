---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  SwitcherMove: true
Damage1: Strength
Damage2: ''
Description: The user strikes its foe, then quickly goes back to safety while another
  party Pokemon takes its place.
DmgType: Physical
Effect: The user switches out after dealing damage. The replacement Pokemon arrives
  to ready to fight. Roll its initiative Switcher Move.
Name: U-Turn
Power: 3
Target: Foe
Type: Bug
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