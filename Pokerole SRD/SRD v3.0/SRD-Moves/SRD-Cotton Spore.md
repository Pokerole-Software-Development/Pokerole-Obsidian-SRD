---
Accuracy1: Clever
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Dexterity
Attributes:
  PowderMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The foe is covered head to toe in cotton fluff, disrupting its movement.
Effect: Single Target. Powder Move. Reduce the Target's Dexterity by 2.
Name: Cotton Spore
Power: 0
Target: Foe
Type: Grass
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