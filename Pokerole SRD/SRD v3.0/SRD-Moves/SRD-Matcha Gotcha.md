---
Accuracy1: Special
Accuracy2: Etiquette
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user invites the foe to a hebal tea ceremony. As the tea is served
  and the foe is off guard, the user throws the hot tea on them, then proceeds to
  enjoy their own cup.
Effect: Single Target. Projectile Move. Low Accuracy 1. The User restores Hp equal
  to half the damage dealt, founded down. Roll 2 Chancce Dice to inflict 1st Degree
  BUrn on the Target. If the user is Frozen solid, destroy the ice bloc.
Name: Matcha Gotcha
Power: 3
Target: All Foes
Type: Grass
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