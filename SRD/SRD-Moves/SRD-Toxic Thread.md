---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Poison
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Dexterity
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user shoots a sticky thread that entangles around the foe, the thread
  is also laced with a potent toxin that will poison the foe on contact.
DmgType: Support
Effect: Reduce Foe's Dexterity. Poison the Foe.
Name: Toxic Thread
Power: 0
Target: Foe
Type: Poison
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