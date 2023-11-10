---
Description: Adds 1 damage dice to Poison type moves.
HealAmount: ''
Name: Toxic Plate
PMDPrice: ''
SpecificPokemon: ''
SuggestedPrice: ''
TypeBonus: Poison
Value: '1'
---

#PokeroleSRD/Items

## `= this.Name`

*`= this.Description`*

| Type Bonus         | Value          | Heal Amount         | Suggested Price         | PMD Price         |
| ------------------ | -------------- | ------------------- | ----------------------- | ----------------- |
| `= this.TypeBonus` | `= this.Value` | `= this.HealAmount` | `= this.SuggestedPrice` | `= this.PMDPrice` |

**Pokemon Limitation**: `= this.SpecificPokemon`
