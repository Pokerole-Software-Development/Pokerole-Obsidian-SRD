---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: User
    Rounds: 1
    Type: Sleep
  Heal:
    Target: Targets
    Type: Complete
    WillPointCost: 1
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: Yeah, this seems like a good spot to take a nap.
Effect: Target Self. Complete Heal. If successful, spend 1 Will point to activate.
  Put the User to Sleep.
Name: Rest
Power: 0
Target: Self
Type: Psychic
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