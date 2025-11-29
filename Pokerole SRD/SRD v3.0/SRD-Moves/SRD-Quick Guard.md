---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  Reaction: '3'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user reacts instinctively and defends itself and its team mates,
  nullyfing the effects of the fastest attacks.
Effect: Target User and Allies in Range. Reaction 3. Shield Move. Reduce 3 Damage
  from a Physical or Special Move with Priority. Negate the Added effects of Reaction
  and late Reaction Moves targeting the User and Allies.
Name: Quick Guard
Power: 0
Target: All Allies
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