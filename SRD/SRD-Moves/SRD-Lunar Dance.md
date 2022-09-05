---
Accuracy1: Insight
Accuracy2: Perform
Damage1: ''
Damage2: ''
Description: The moon shines at the darkest hours, reflecting the sun's lifebringer
  light on those who fell into the night, taking pity on their lost souls.
DmgType: Support
Effect: The user Faints. One fallen Ally regains consciousness, has its HP fully restored
  and all Status Ailments healed. If the Ally was not in-battle, it is called out
  and ready to fight.
Name: Lunar Dance
Power: 0
Target: One Ally
Type: Psychic
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