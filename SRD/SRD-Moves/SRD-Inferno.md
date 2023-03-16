---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Burn3
Attributes:
  AccuracyReduction: 3
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon sets the foe on fire. These flames rise up to 6 feet. A very
  dangerous Move.
Effect: Lethal. Apply Burn 3 to the Foe. -3 Accuracy.
Name: Inferno
Power: 4
Target: Foe
Type: Fire
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