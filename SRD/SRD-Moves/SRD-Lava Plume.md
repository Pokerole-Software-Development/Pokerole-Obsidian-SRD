---
Accuracy1: Dexterity
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: The user shoots up bits of molten lava that fall scattered around the
  field.
DmgType: Special
Effect: Roll 3 Chance Dice to Burn those affected.
Name: Lava Plume
Power: 3
Target: Area
Type: Fire
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