---
Category: Healing
Description: A single-use capsule of formula. The pokemon won't be able to restore
  health further until the next day.
HealthRestored: 99
ItemSprite: SRD-max-potion-ItemSprite.png
Name: Max Potion
OneUse: false
PMD: false
Pocket: Medicine
Source: Core 2.0
TrainerPrice: '1700'
---

#PokeroleSRD/Items

## `= this.Name`

![[SRD-max-potion-ItemSprite.png|right]]

*`= this.Description`*

| Trainer Price           | PMD Price         | Source | 
| ----------------------- | ----------------- | ------ |
| `= this.SuggestedPrice` | `= this.PMDPrice` | `= this.Source`

**Pokemon Limitation**: `= this.SpecificPokemon`
