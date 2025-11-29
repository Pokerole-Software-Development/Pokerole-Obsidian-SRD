---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Flinch
Attributes:
  Reaction: '1'
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon pretends to be getting ready for the battle when they\
  \ are actually prepairing a surprise attack on the foe."
Effect: Single Target. Reaction 1. Flinch the Target. This Move will only work on
  the First Round the User is out in battle. from the Second Round on, it will fail
  automatically.
Name: Fake Out
Power: 2
Target: Foe
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