---
Accuracy1: VITALITY
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: The sun shines brightly on the Pokemon and makes it feel rejuvenated
  like early in the morning.
DmgType: SUPPORT
Effect: Basic Heal. If successful spend 1 Will point to activate. Complete Heal during
  Sunny Weather. If Rain/Sandstorm Weather is in effect or it's night or you are indoors/underground
  this move only heals 1 HP.
Name: Morning Sun
Power: 0
Target: User
Type: Normal
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`