---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  PhysicalRanged: true
  Ranged: true
  Reaction: '1'
Category: Physical
Damage1: Strength
Damage2: ''
Description: "With extraordinary swiftness, the Pok\xE9mon shoots an ice bullet like\
  \ the fastest gun in the North Pole."
Effect: Single Target. Reaction 1. Ranged.
Name: Ice Shard
Power: 2
Target: Foe
Type: Ice
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