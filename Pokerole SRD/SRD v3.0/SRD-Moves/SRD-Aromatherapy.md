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
  - BadlyPoison
  - Sleep
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon releases a series of essential oils and herbal scents\
  \ to refresh themselves and their companions."
Effect: Target User and Allies in Range. Cure Status Ailments (All Burn degrees, Freeze,
  Paralysis, All Poison & Sleep) on the Targets.
Name: Aromatherapy
Power: 0
Target: All Allies
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