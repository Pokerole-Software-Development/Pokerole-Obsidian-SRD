---
Accuracy1: Clever
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  LateReaction: '6'
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon takes advantage of their foe preparing to attack to unleash\
  \ a dirty surprise blow."
Effect: Single Target. Late Reaction 6. *This move can only be used as a Late Reaction;
  and only if the Target used a Physical or Special Move, otherwise it will fail.
Name: Sucker Punch
Power: 3
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