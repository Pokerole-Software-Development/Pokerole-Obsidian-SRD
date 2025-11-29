---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  Reaction: '1'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon uses a mat as a shield."
Effect: Target User and Allies in Range. Shield Move. Reaction 1. Reduce 3 Damage
  from a Physical or Special Move.
Name: Mat Block
Power: 0
Target: All Allies
Type: Fighting
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