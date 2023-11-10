---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  NeverFail: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon rises up in the air towards a light source, momentarily blinding
  the foe, then plummets quickly to attack the opponent.
Effect: Never Fail.
Name: Aerial Ace
Power: 2
Target: Foe
Type: Flying
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