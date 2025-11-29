---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: The user electrifies the battlefield, making it impossible to relax around
  the sparks and live current.
Effect: Target Battlefield. Add 1 Extra Damage Dice to all Physical & Special Electric-Type
  Moves. Pokemon without immunity to Ground will be cured of the Sleep Status. Duration
  4 Rounds.
Name: Electric Terrain
Power: 0
Target: Battlefield
Type: Electric
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