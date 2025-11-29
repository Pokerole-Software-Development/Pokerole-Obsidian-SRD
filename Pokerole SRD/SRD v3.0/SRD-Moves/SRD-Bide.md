---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: User
    Type: Bide
Attributes: {}
Category: Physical
Damage1: Varies
Damage2: ''
Description: The user puts up with being hit, waiting for the perfect opportunity
  to retaliate.
Effect: Single Target. The User will not Evade or Clash the next 2 Physical or Special
  Moves targeting it. Once all damage has been dealt against the User, roll a number
  of Normal-Type Damage dice equal to twice the total amount of Damage the Target
  received. Ignore Defenses.
Name: Bide
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