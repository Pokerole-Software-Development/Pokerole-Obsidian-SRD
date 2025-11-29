---
Accuracy1: Insight
Accuracy2: Stealth
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  BlockDamagePool: 0
  Duration: wholeScene
  EntryHazard: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon moves stealthily and without raising suspicion. By the\
  \ time the enemy realizes it, the entire field is covered in cobwebs."
Effect: Target Foe's Side of the Field. Entry Hazard. Blocks. Whole Scene Duration.
Name: Spider Web
Power: 0
Target: Foe's Battlefield
Type: Bug
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