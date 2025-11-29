---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Endure
Attributes:
  Reaction: '5'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon mentally prepares to receive a fatal blow, their spirit\
  \ is stronger than their body so they endure to keep on fighting for as long as\
  \ possible."
Effect: Target Self. Reaction 5. Shield Move. If a Physical or Special Move would
  cause the user to faint, they remain at 1 HP instead, remove this effect afterwards.
  The effect re-activates on the user's next Turn. Whole Round duration.
Name: Endure
Power: 0
Target: Self
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