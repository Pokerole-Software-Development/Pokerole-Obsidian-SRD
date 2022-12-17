---
Accuracy1: Beauty
Accuracy2: Allure
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Infaturate
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user makes use of its good looks and attitude to infatuate its foe.
DmgType: Support
Effect: If Successful, Target is now In Love. This Move fails if target is from same
  gender as the User or genderless.
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

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`