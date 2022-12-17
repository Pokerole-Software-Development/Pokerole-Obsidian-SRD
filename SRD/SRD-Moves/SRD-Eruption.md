---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
Damage1: Special
Damage2: ''
Description: A fierce burst of lava coming from the user at full force charring whatever
  comes in contact with it.
DmgType: Special
Effect: Lethal. Reduce 1 Dice from the Damage Pool for every missing HP the User has.
  Up to 5 dice may be removed this way.
Name: Eruption
Power: 6
Target: All Foes
Type: Fire
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`