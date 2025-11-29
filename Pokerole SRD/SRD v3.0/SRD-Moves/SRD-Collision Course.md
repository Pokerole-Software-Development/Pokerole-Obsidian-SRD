---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Lethal: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: Koraidon dashes through the field with a screeching sound, it will not
  stop until it violently crashes. Causing a massive prehistoric explosion.
Effect: Single Target. Lethal. Unique. *Add 4 Extra Dice to the Damage pool of this
  Move if the Target is weak to Fight-Type Moves.
Name: Collision Course
Power: 4
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