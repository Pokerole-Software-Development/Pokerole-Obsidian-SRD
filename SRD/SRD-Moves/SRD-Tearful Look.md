---
Accuracy1: CUTE
Accuracy2: ALLURE
Damage1: ''
Damage2: ''
Description: The Pokemon's eyes start watering as if it were about to cry, it's foe
  is moved by the tears and loses its will to fight.
DmgType: SUPPORT
Effect: Reduce Foe's Strength and Special.
Name: Tearful Look
Power: 0
Target: Foe
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