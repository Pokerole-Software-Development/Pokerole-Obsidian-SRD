---
Accuracy1: Tough
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Strength
    - Dexterity
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user performs a vigorous and mystical dance that boosts the fighting
  spirit and reflexes.
Effect: Increase the User's Strength and Dexterity.
Name: Dragon Dance
Power: 0
Target: User
Type: Dragon
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