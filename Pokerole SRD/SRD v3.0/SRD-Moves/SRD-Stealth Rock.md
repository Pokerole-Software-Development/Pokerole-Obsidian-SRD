---
Accuracy1: Insight
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  EntryHazard: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon hides a trap of sharp rocks that are launched at the\
  \ victim before they even realize what even happened."
Effect: Target Foe's Side of the Field. Entry Hazard. Pokemon entering the battle
  Receive 1 Rock-Type Damage. This effect does not stack.
Name: Stealth Rock
Power: 0
Target: Foe's Battlefield
Type: Rock
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