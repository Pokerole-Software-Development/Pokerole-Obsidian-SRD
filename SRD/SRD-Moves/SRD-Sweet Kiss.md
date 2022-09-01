---
Accuracy1: CUTE
Accuracy2: ALLURE
Damage1: ''
Damage2: ''
Description: The Pokemon moves towards the foe and plants a delicate kiss on its cheek,
  then leaves playfully. The foe struggles to know what it meant.
DmgType: SUPPORT
Effect: Confuse the foe. -2 Accuracy.
Name: Sweet Kiss
Power: 0
Target: Foe
Type: Fairy
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