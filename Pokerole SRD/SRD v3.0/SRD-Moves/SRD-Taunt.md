---
Accuracy1: Tough/Cute
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Taunt
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: Through tease and mockery, the foe is enraged to the point it stops thinking
  clearly.
Effect: Single Target. The Target cannot perform Support Moves (Support Maneuvers
  may still be performed). Duration 4 Rounds.
Name: Taunt
Power: 0
Target: Foe
Type: Dark
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