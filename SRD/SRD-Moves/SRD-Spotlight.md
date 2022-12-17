---
Accuracy1: Cool
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: FollowMeSpotlight
Attributes:
  Priority: 3
Damage1: ''
Damage2: ''
Description: The user points a focused light onto one of its allies as if it were
  on a stage, the ally can't help but catch everyone's attention into itself.
DmgType: Support
Effect: Priority 3. Foes will target One Ally this turn.
Name: Spotlight
Power: 0
Target: One Ally
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