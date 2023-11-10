---
Description: Adds 2 damage dice to Dragon type moves. Will be immediately consumed
  on move use.
HealAmount: ''
Name: Dragon Gem
PMDPrice: ''
SpecificPokemon: ''
SuggestedPrice: ''
TypeBonus: Dragon
Value: '2'
---

#PokeroleSRD/Items

## `= this.Name`

*`= this.Description`*

| Type Bonus         | Value          | Heal Amount         | Suggested Price         | PMD Price         |
| ------------------ | -------------- | ------------------- | ----------------------- | ----------------- |
| `= this.TypeBonus` | `= this.Value` | `= this.HealAmount` | `= this.SuggestedPrice` | `= this.PMDPrice` |

**Pokemon Limitation**: `= this.SpecificPokemon`
