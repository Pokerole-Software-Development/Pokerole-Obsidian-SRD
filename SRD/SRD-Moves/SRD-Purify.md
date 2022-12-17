---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  AilmentHeal:
  - All
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon is covered by a gelatinous goo that can be used to treat
  several ailments, the Pokemon also uses it as a source of nourishment.
DmgType: Support
Effect: Heal a Target's Status Ailment. If you do then the user may heal 1 HP.
Name: Purify
Power: 0
Target: Foe
Type: Poison
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`