---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: SpedUp
Attributes:
  Duration: wholeScene
  Vulnerable: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon compacts their body. Becoming a much smaller target to\
  \ be difficult to hit. But a well placed stomp may leave them squished on the floor,\
  \ though."
Effect: 'Target Self. The User can now make up to 5 Evasions per Round. Reduce the
  User''s Height and Weight in half. The user is now Vulernable to: Stomp. Whole Scene
  Duration.'
Name: Minimize
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