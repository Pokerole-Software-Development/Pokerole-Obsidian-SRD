---
Accuracy1: Beauty
Accuracy2: Charm
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Infatuate
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "Through their good looks and coquetish attitude, the Pok\xE9mon makes\
  \ everyone develop a crush on them."
Effect: Single Target. Target is now In Love with the User.
Name: Attract
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