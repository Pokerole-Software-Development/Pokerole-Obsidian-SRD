---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  BiteMove: true
  DestroyShield: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon bares its fangs to bite the foe, psychic energy begins\
  \ piercing before the actual fangs make contact."
Effect: Single Target. Bite Move. If there is a Force Field on the Target's side of
  the field, destroy it.
Name: Psychic Fangs
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