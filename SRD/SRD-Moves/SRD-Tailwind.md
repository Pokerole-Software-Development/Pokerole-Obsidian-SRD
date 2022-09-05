---
Accuracy1: Insight
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: User flaps its wings and casts a turbulent wind that helps the team move
  significantly faster.
DmgType: Support
Effect: For the Next 4 Rounds, Increase the Dexterity of the User and All Allies in
  the field by 2.
Name: Tailwind
Power: 0
Target: Battlefield
Type: Flying
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