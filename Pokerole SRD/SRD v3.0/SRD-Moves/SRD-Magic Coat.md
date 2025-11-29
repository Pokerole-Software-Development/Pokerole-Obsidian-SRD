---
Accuracy1: Special
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  Reaction: '4'
Category: Support
Damage1: ''
Damage2: ''
Description: "Through a swift mind trick the Pok\xE9mon trick the foe into pouring\
  \ their ill intent on itself."
Effect: Target Self. Reaction 4. Support Moves that would target the user or its side
  of the field are inflicted to the foe performing the Move or that foe's side of
  the field instead.
Name: Magic Coat
Power: 0
Target: Foe's Battlefield
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