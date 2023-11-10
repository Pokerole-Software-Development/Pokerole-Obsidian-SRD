---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  AilmentHeal:
  - Burn1
  - Burn2
  - Burn3
  - Freeze
  - Paralysis
  - Poison
  - Sleep
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon releases medicinal scents and vapors to refresh the user
  and its allies.
Effect: Cure User and Allies from Burn, Freeze, Paralysis, Poison, or Sleep.
Name: Aromatherapy
Power: 0
Target: User and Allies
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