---
Accuracy1: Dexterity
Accuracy2: Channel/Stealth
AddedEffects: {}
Attributes:
  Reaction: '1'
  SuccessiveActions: true
Category: Special
Damage1: Special
Damage2: ''
Description: The best ninjas attack swiftly and undetected, after the deed is done,
  no evidence is left but an inconspicuous puddle of water.
Effect: Single Target. Reaction 1. Successive Actions.
Name: Water Shuriken
Power: 1
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