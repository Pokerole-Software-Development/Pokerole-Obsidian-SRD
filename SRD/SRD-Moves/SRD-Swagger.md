---
Accuracy1: Tough
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Confuse
  StatChanges:
  - Affects: Targets
    Stages: 2
    Stats:
    - Strength
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon enrages the foe with its arrogant demeanor, making it lose
  focus in battle.
DmgType: Support
Effect: Increase the foe's Strength by 2. Inflicts Confusion.
Name: Swagger
Power: 0
Target: Foe
Type: Normal
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