---
Description: When hit by a move the Pokemon is weak to, increase Strength and Special
  by 2.
HealAmount: ''
Name: Weakness Policy
PMDPrice: ''
SpecificPokemon: ''
SuggestedPrice: ''
TypeBonus: ''
Value: ''
---

#PokeroleSRD/Items

## `= this.Name`

*`= this.Description`*

| Type Bonus         | Value          | Heal Amount         | Suggested Price         | PMD Price         |
| ------------------ | -------------- | ------------------- | ----------------------- | ----------------- |
| `= this.TypeBonus` | `= this.Value` | `= this.HealAmount` | `= this.SuggestedPrice` | `= this.PMDPrice` |

**Pokemon Limitation**: `= this.SpecificPokemon`
