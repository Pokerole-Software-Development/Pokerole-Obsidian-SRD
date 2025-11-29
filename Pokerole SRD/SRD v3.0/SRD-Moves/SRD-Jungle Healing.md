---
Accuracy1: Special
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
  Heal:
    Target: Targets
    Type: Basic
    WillPointCost: 1
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: A stream of life force from plants and trees flow into the User and their
  Allies.
Effect: Target User and Allies in Range. Heal any Status Ailment (Burn, Freeze, Paralysis,
  Poison & Sleep) on the Targets. Restore 1 HP to the targets. If successful spend
  1 Will point to activate.
Name: Jungle Healing
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