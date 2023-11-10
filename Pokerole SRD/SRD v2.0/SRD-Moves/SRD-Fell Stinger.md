---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 2
    Stats:
    - Strength
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon stings the target. If the foe is too weakened to move it
  absorbs part of its power.
Effect: If the foe faints due to damage from this attack increase the user's Strength
  by 2.
Name: Fell Stinger
Power: 1
Target: Foe
Type: Bug
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