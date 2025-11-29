---
Accuracy1: Tough
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Embargo
Attributes:
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: "The user demands the held item of a Pok\xE9mon and the items in the\
  \ bag of their trainer. Scared, both Pok\xE9mon and Trainer comply"
Effect: Single Target. The Target loses its Held Item. Target's Trainer & Partners
  can't use Items on the Target. Whole Scene Duration.
Name: Embargo
Power: 0
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