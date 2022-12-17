---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Target
    Type: WorrySeed
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user plants a seed in its foe. It causes a restless preoccupation
  that won't let it sleep at night.
DmgType: Support
Effect: Until the end of the Scene. Target's Ability is now "Insomnia".
Name: Worry Seed
Power: 0
Target: Foe
Type: Grass
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