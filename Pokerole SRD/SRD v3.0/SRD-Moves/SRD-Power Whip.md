---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -2
Category: Physical
Damage1: Strength
Damage2: ''
Description: A thick vine full of thorns is waved as a whip against the enemy. As
  devastating as the blow would be, the incoming attack is easily percieved by the
  foe.
Effect: Single Target. Low Accuracy 2.
Name: Power Whip
Power: 5
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