---
Accuracy1: Tough/Cute
Accuracy2: Intimidate
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Strength
Attributes:
  SoundMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: Either through a menacing attitude or an adorable demeanor, the foe will
  hesitate to attack the user at full power.
Effect: Target All Foes in Range. Sound Move. Reduce by 1 the Strength of those affected.
Name: Growl
Power: 0
Target: All Foes
Type: Normal
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