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
Description: "The Pok\xE9mon becomes a giant energy shield that pushes back everything\
  \ in its wake. If the foe is under the effects of the Dynamax phenomenon all its\
  \ energy will be swept away"
Effect: Single Target. Unique. *If the Foe is under the effects of Dynamax/Gigantamax,
  This Move becomes Lethal and add 4 Extra Dice to the Damage Pool.
Name: Behemoth Bash
Power: 4
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