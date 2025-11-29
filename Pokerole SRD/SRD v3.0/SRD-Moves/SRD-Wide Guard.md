---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Reaction: '3'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon uses their whole body to provide shelter and protection\
  \ to everyone they can. They are the rock on which others stand."
Effect: Target User and Allies in Range. Reaction 3. Shield Move. Reduce 3 Damage
  the Targets would receive from Physical or Special Move. Negate the Added Effects
  of Any Moves on the Targets.
Name: Wide Guard
Power: 0
Target: All Allies
Type: Rock
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