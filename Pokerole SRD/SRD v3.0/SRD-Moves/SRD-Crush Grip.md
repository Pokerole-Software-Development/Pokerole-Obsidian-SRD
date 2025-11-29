---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Lethal: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon grips the foe and starts crushing it. Small targets are\
  \ difficult to grasp but larger bodies will not be released until they break. "
Effect: Single Target. Lethal. Unique. *If the foe has an HP higher than 4, add 1
  Extra Die to the Damage pool for every exceeding point. Up to 9 Dice may be added
  this way.
Name: Crush Grip
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