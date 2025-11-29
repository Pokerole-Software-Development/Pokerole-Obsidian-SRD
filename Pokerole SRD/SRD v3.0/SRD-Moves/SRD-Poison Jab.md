---
Accuracy1: Dexterity
Accuracy2: Brawl/Stealth
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Poison
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon is set on injecting venom directly into the foe\u2019\
  s bloodstream. They can do it the easy way or the hard way."
Effect: Single Target. Roll 3 Chance Dice to Poison the Target.
Name: Poison Jab
Power: 3
Target: Foe
Type: Poison
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