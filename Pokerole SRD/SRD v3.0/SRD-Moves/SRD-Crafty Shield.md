---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects: {}
Attributes:
  Reaction: '3'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon creates a magic shield to protect everyone from any tricks\
  \ a foe has up their sleeve. Under this shield, everyone can see dishonesty and\
  \ bad intentions"
Effect: Target User and Allies in Range. Reaction 3. Shield Move. Negate the Added
  Effects from Moves made against the Targets.
Name: Crafty Shield
Power: '0 '
Target: All Allies
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