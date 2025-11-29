---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: When you have a hammer everything is a nail.
Effect: Single Target. Lethal. This Move will fail if it was used the previous Round.
  *This Move may deal 2 Extra Damage Dice to Steel-Type Pokemon at Storyteller's Discretion.
Name: Gigaton Hammer
Power: 7
Target: Foe
Type: Steel
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