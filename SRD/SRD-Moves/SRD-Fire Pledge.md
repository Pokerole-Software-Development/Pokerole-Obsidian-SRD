---
Accuracy1: Dexterity
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: The Pokemon chants to invoke the power of Fire. Its pledge is heard,
  then the flames consume everything around.
DmgType: Special
Effect: All flammable plants and objects in the battlefield are covered in flames.
  Roll 1 Dice of Fire Damage at the end of every Round against everyone on the field.
Name: Fire Pledge
Power: 2
Target: Battlefield and Area
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