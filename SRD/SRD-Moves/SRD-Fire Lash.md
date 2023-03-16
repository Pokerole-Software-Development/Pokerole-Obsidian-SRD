---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Def
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: With a whip of fire, the Pokemon ensnares its foe, who is left defenseless
  and at its mercy.
Effect: Reduce Foe's Defense.
Name: Fire Lash
Power: 3
Target: Foe
Type: Fire
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