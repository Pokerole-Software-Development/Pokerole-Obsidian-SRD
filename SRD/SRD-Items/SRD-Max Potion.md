---
Description: A single-use capsule of formula. The pokemon won't be able to restore
  health further until the next day.
HealAmount: Full
Name: Max Potion
PMDPrice: ''
SpecificPokemon: ''
SuggestedPrice: '1700'
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
