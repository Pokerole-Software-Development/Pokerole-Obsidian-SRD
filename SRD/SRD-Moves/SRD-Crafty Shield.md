---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects: {}
Attributes:
  Priority: 3
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon creates a magic shield to protect everyone from the bad tricks
  a foe might have under its sleeve. Under this shield, everyone can see dishonesty
  and bad intentions.
Effect: Priority 3. The User and its Allies are protected from the effects of a Support
  Move. Shield.
Name: Crafty Shield
Power: 0
Target: User and Allies
Type: Fairy
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