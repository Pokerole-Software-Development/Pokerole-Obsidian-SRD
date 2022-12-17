---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
Damage1: Special
Damage2: ''
Description: The User unleashes all of its might through a massive blast of raging
  fire. Although the damage is devastating the Pokemon is left unable to produce more
  fire for at least a day.
DmgType: Special
Effect: Lethal. After Damage is dealt, the user is no longer considered a Fire-Type
  for the rest of the day (if its only type was Fire, it is now considered Typeless).
  Fire-type Moves won't add their Power to the Damage pool of this Pokemon for the
  rest of the day.
Name: Burn Up
Power: 7
Target: Foe
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