---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Burn2
Attributes:
  Lethal: true
Damage1: Special
Damage2: ''
Description: The User torches everything around itself in a sudden burst of scarlet
  flames. Everything is brought to cinders in a matter of seconds.
DmgType: Special
Effect: Lethal. All Foes in Range. Roll 3 Chance Dice to Apply Burn 2 those Affected.
Name: Searing Shot
Power: 5
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