---
Accuracy1: Insight
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: The Pokemon quickly covers the arena with a sticky web, newly arrived
  foes will have trouble moving with ease.
DmgType: Support
Effect: Entry Hazard. Foe Pokemon that enter the battlefield get a Dexterity Reduction
  of 1. Pokemon with the Levitate ability and Flying Type Pokemon are immune to this
  effect.
Name: Sticky Web
Power: 0
Target: Battlefield
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