---
Accuracy1: Insight
Accuracy2: Alert
AddedEffects: {}
Attributes:
  Reaction: '5'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon detects the intentions of the attacker and reacts just\
  \ in time to minimize the damage."
Effect: Target Self. Reaction 5. Shield Move. Reduce 3 Damage this Pokemon would receive
  from a Physical or Special move. Negate the Added Effcts of Any Moves that target
  the user.
Name: Detect
Power: 0
Target: Self
Type: Fighting
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