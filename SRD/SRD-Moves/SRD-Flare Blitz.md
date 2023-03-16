---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Burn3
Attributes:
  Recoil: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user sets itself on fire, recklessly charging against the target
  with a brutal strike.
Effect: Recoil. Roll 1 Chance Dice to Apply Burn 3 to the foe.
Name: Flare Blitz
Power: 5
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