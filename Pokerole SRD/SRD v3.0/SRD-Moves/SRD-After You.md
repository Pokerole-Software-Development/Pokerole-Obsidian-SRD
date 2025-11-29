---
Accuracy1: Cool
Accuracy2: Etiquette
AddedEffects: {}
Attributes:
  Duration: wholeScene
  Reaction: '1'
Category: Support
Damage1: ''
Damage2: ''
Description: The user bows and courteously lets a friend go first.
Effect: Target One Ally. Reaction 1. The Target will go First in the Initiative Order.
  If used again, the previous target reverts to their original Initiative order. Whole
  Scene Duration.
Name: After You
Power: 0
Target: Ally
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