---
Accuracy1: Strength
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  Charge: true
  IgnoreShield: true
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon disappears into a dark dimension to infiltrate even the\
  \ most impenetrable fortress. It may reappear during its next action."
Effect: Single Target. Charge move. Out of Range while Charging. Lethal. Ignore any
  Cover, Shield Moves, and/or Force Fields active on the Target.
Name: Phantom Force
Power: 3
Target: Foe
Type: Ghost
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