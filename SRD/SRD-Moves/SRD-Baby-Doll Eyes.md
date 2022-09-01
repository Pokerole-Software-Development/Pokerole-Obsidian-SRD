---
Accuracy1: CUTE
Accuracy2: ALLURE
Damage1: ''
Damage2: ''
Description: Before anyone acts in battle, the user looks at the foe with the cutest
  eyes.
DmgType: SUPPORT
Effect: Priority 1. Reduce foe's Strength.
Name: Baby-Doll Eyes
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