---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  Reaction: '1'
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon propels themselves with a jet of pressured water."
Effect: Single Target. Reaction 1.
Name: Aqua Jet
Power: 2
Target: Foe
Type: Water
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