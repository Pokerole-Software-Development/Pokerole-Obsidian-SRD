---
Category: ''
Description: A map with the marked routes, cities and Pokemon Centers of the region
  you are in.
ItemSprite: SRD-regional-map-ItemSprite.png
Name: Regional Map
OneUse: false
PMD: false
Pocket: TrainerItems
Source: Core 2.0
TrainerPrice: '50'
---

#PokeroleSRD/Items

## `= this.Name`

![[SRD-regional-map-ItemSprite.png|right]]

*`= this.Description`*

| Trainer Price           | PMD Price         | Source | 
| ----------------------- | ----------------- | ------ |
| `= this.SuggestedPrice` | `= this.PMDPrice` | `= this.Source`

**Pokemon Limitation**: `= this.SpecificPokemon`
