---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  BiteMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "This Pok\xE9mon uses their gills to snap at its target. Even if they\
  \ don\u2019t have teeth, their jaws have a crushing strength."
Effect: Single Target. Bite Move. *If this is the first Action of the Round for the
  User, add 2 Extra Dice to the Damage pool of this Move.
Name: Fishious Rend
Power: 3
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