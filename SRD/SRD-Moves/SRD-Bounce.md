---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Paralyze
Attributes:
  Charge: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon will jump 30 feet in the air before landing on top of the
  foe. The user won't suffer any falling damage.
Effect: Charge Move. While charging this Move, the user will be out of range. Roll
  3 Chance Dice to Paralyze the foe.
Name: Bounce
Power: 3
Target: Foe
Type: Flying
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