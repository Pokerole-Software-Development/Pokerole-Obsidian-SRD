---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Freeze
Attributes: {}
Damage1: Special
Damage2: ''
Description: The user sends out a wind current full of snowflakes that freeze whatever
  they touch. This powder can easily turn a room to ice.
DmgType: Special
Effect: Roll 1 Chance Dice to Freeze those affected.
Name: Powder Snow
Power: 2
Target: All Foes
Type: Ice
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