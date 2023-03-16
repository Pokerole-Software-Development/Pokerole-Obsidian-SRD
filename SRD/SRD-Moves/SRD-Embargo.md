---
Accuracy1: Tough
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Embargo
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user quickly takes out the held item of a Pokemon. It also empties
  the bag of the trainer and forces everyone to stay away from their own properties.
  Evildoers master this Move.
Effect: The target cannot use its held item nor can its trainer use items on it.
Name: Embargo
Power: 0
Target: Foe
Type: Dark
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