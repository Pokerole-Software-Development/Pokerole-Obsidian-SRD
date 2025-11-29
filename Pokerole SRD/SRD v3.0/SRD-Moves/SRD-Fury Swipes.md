---
Accuracy1: Dexterity
Accuracy2: Brawl/Intimidate
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  SuccessiveActions: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "With their sharp claws, the Pok\xE9mon will swiftly scatch their foe,\
  \ leaving its face full of small cuts."
Effect: Single Target. Low Accuracy 1. Successive Actions.
Name: Fury Swipes
Power: 1
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