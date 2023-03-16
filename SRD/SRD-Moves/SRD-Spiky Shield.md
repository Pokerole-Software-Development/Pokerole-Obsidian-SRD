---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Priority: 3
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon covers itself with a thorn filled shell, the foe will be
  damaged if it hits directly into it.
Effect: Priority 3. Shield. Reduce 3 Damage from the next attack and deal 2 Damage
  Dice to the attacker if it used a physical non-ranged Move.
Name: Spiky Shield
Power: 0
Target: User
Type: Grass
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`