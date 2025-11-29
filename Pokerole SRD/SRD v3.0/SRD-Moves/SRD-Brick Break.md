---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  DestroyShield: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon uses a karate technique to chop through tall piles of\
  \ bricks. No matter how many layers you pile up, they\u2019ll break regardless."
Effect: Single Target. *If there is a Force field on the Target's side of the field,
  destroy it and add 2 Extra Dice to the Damage Pool.
Name: Brick Break
Power: 3
Target: Foe
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