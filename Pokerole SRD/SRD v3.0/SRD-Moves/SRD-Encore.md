---
Accuracy1: Cool
Accuracy2: Charm/Etiquette
AddedEffects: {}
Attributes:
  Duration: 4
  Reaction: '3'
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon makes a standing ovation at their target, prompting them\
  \ to repeat everything they just did, exactly the way they did it."
Effect: Single Target. Reaction 3. The Target will repeat the exact same action sequence
  it had last Round. Target must have had an action sequence. Duration 1 Round. If
  used on the previous Round, this move fails. See more on p. 529.
Name: Encore
Power: 0
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