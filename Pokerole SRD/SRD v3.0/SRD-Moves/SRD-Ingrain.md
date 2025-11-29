---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Ingrain
Attributes:
  BlockDamagePool: 0
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon roots themselves to absorb nutrients directly from the\
  \ ground."
Effect: Target Self. The User heals 1 HP at the end of each Round. Spend 1 Will point
  to activate. Blocks. Whole Scene Duration.
Name: Ingrain
Power: 0
Target: Self
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