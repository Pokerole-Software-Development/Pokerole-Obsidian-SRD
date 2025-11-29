---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  HurtBonus: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user gathers their mettle to block away the pain and focus only on
  hitting harder.
Effect: Single Target. *Add 1 Extra Die to the Damage Pool for every missing HP the
  User has. Up to 5 Dice may be added this way.
Name: Reversal
Power: 1
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