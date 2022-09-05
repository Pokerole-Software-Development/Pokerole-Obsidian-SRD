---
Accuracy1: Dexterity
Accuracy2: Brawl
Damage1: Strength
Damage2: ''
Description: The Pokemon hurls an anchor towards its foe and entangles it with seaweed,
  the anchor drags the foe down so it cannot escape.
DmgType: Physical
Effect: Ranged. Blocks.
Name: Anchor Shot
Power: 3
Target: Foe
Type: Steel
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