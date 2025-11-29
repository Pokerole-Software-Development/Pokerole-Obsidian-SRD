---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  ProjectileMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon spits out a red syrup on their foe; as the syrup hardens\
  \ the movement of the foe becomes impaired until they become a sweet caramelized\
  \ statue."
Effect: Single Target. Low Accuracy 1. Projectile Move. Reduce the Target's Dexterity
  by 1. *This effect can stack up to 3 Times.
Name: Syrup Bomb
Power: 2
Target: Foe
Type: Grass
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