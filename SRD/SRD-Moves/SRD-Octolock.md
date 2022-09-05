---
Accuracy1: Strength
Accuracy2: Brawl
Damage1: ''
Damage2: ''
Description: The user wraps its tentacles to immobilize the foe. Being so close enables
  the user to find weak spots.
DmgType: Support
Effect: Block. Reduce the foe's Defense and Sp. Defense.
Name: Octolock
Power: 0
Target: Foe
Type: Fighting
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