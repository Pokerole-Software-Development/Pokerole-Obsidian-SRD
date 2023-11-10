---
Description: Poison type Pokemon may heal 1 hp as a bonus action. This can be done
  10 times before depleting. Non-poison types take 1 damage per turn from holding
  this.
HealAmount: ''
Name: Black Sludge
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
