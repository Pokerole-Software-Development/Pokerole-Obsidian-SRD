---
Accuracy1: Insight
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Freeze
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon shoots freakin\u2019 laser beams from its freakin\u2019\
  \ eyes against everything that moves...until nothing does."
Effect: Single Target. Roll 1 Chance Die to Freeze the Target.
Name: Freezing Glare
Power: 3
Target: Foe
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