---
Accuracy1: INSIGHT
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The Pokemon foresses something terrible happening to the target. It may
  see images from its own future without any risk.
DmgType: SPECIAL
Effect: Strikes at the end of the next Round. It bypasses any Shield Move and cover.
  If the target retires or switches out from battle the damage will be dealt to the
  next opponent or to one of its allies.
Name: Future Sight
Power: 5
Target: Foe
Type: Psychic
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