---
Category: ''
Description: A basic ball for catching pokemon and carrying heavy items.
Image: SRD-pokeball-ItemSprite.png
Name: Pokeball
OneUse: true
PMD: false
Pocket: Pokeballs
Source: Core 2.0
TrainerPrice: '200'
---

#PokeroleSRD/Items

## `= this.Name`

![[SRD-pokeball-ItemSprite.png|right]]

*`= this.Description`*

| Trainer Price           | PMD Price         | Source | 
| ----------------------- | ----------------- | ------ |
| `= this.SuggestedPrice` | `= this.PMDPrice` | `= this.Source`

**Pokemon Limitation**: `= this.SpecificPokemon`
