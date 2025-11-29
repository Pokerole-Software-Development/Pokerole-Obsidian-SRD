---
Accuracy1: Clever
Accuracy2: Perform
AddedEffects: {}
Attributes:
  CopyMove: true
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon is a quick learner. They imitate their target\u2019s\
  \ movements and just like that they get a new set of powers."
Effect: Single Target. Copy Move. Replace "Mimic" with the copied Move. Whole Scene
  Duration.
Name: Mimic
Power: 0
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