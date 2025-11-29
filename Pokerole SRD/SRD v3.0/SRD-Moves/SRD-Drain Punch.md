---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects:
  Heal:
    Percentage: 0.5
    Target: User
    Type: Leech
Attributes:
  FistMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: A solid punch that weakens the foes and revitalizes the user with each
  hit.
Effect: Single Target. Fist Move. The User restores HP equal to half the damage dealt,
  rounded down.
Name: Drain Punch
Power: 3
Target: Foe
Type: Fighting
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