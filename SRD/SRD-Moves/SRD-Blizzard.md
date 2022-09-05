---
Accuracy1: Special
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: The user swirls a violent gelid wind around the foes. This blizzard may
  not last long, but it is tremendously strong.
DmgType: Special
Effect: Roll 1 Chance Dice to Freeze those affected. If performed under Hail Weather
  Ignore this moves Reduced Accuracy and the Move can't be evaded. If performed under
  Sunny Weather Accuracy becomes -3 instead. -2 Accuracy.
Name: Blizzard
Power: 5
Target: All Foes
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