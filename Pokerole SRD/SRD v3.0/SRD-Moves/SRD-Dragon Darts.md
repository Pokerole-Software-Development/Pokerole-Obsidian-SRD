---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  DoubleAction: true
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon\u2019s head is a nest for its less evolved forms, the\
  \ younglings will sometimes be used as projectiles."
Effect: Single Target. Ranged. Double Action.
Name: Dragon Darts
Power: 2
Target: Foe
Type: Dragon
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