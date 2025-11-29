---
Accuracy1: Dexterity
Accuracy2: Charm
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Paralyze
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon gives a cute nuzzle at their target, it looks adorable\
  \ until you see the sparks."
Effect: Single Target. Paralyze the foe.
Name: Nuzzle
Power: 1
Target: Foe
Type: Electric
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