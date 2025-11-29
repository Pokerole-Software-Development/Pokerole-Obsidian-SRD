---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Recoil: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Without regard for their own safety, the Pok\xE9mon does a reckless\
  \ attack against their foe."
Effect: Single Target. Recoil.
Name: Double-Edge
Power: 5
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