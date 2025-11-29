---
Accuracy1: Beauty
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: 2
    Stats:
    - Strength
    - Special
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "With just a bit of cake frosting the Pok\xE9mon decorates their target\
  \ to look bigger, more powerful and incredibly delicious!"
Effect: Target One Ally. Increase by 2 the Strength and Special of the Target.
Name: Decorate
Power: 0
Target: Ally
Type: Fairy
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