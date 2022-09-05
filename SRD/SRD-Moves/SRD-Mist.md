---
Accuracy1: Special
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: The user cloaks itself and its allies within cold mist with mystic properties,
  it may conceal whoever is nearby.
DmgType: Support
Effect: For the next 4 Rounds, the User and Allies cannot have their Attributes or
  Traits reduced.
Name: Mist
Power: 0
Target: User and Allies
Type: Ice
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