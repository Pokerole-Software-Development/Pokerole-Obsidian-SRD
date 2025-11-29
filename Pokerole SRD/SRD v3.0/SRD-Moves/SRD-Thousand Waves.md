---
Accuracy1: Strength
Accuracy2: Channel/Stealth
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  BlockDamagePool: 0
  Duration: wholeScene
  PhysicalRanged: true
  Ranged: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Solid ground becomes a sandtrap, cracked earth will close to ensnare\
  \ your feet. It\u2019s as if the land itself wanted to trap you. There is no attacker\
  \ nor escape in sight."
Effect: Target All Foes in Range. Ranged. Unique. Blocks. Whole Scene Duration.
Name: Thousand Waves
Power: 3
Target: All Foes
Type: Ground
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