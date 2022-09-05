---
Accuracy1: Beauty
Accuracy2: Allure
Damage1: ''
Damage2: ''
Description: "The Pokemon shows off its attractiveness and even flirts with the opponents,\
  \ those who fall for its charms can\u2019t focus on the battle."
DmgType: Support
Effect: If the affected targets are from the opposite gender, Reduce their Special
  by 2.
Name: Captivate
Power: 0
Target: All Foes
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