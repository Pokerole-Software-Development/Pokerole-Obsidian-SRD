---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 1
    Stages: -1
    Stats:
    - Def
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon uses its sharp shell as a weapon to cut the target's fur,
  armor or anything protecting its body.
Effect: Roll 1 Chance Dice to Reduce the foe's Defense.
Name: Razor Shell
Power: 3
Target: Foe
Type: Water
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