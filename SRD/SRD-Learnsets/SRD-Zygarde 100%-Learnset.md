---
DexID: 0719
Moves:
- - Master
  - '[[SRD-Glare|Glare]]'
- - Master
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Master
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Dig|Dig]]'
- - Master
  - '[[SRD-Bind|Bind]]'
- - Master
  - '[[SRD-Land''s Wrath|Land''s Wrath]]'
- - Master
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Master
  - '[[SRD-Haze|Haze]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Earthquake|Earthquake]]'
- - Master
  - '[[SRD-Camouflage|Camouflage]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Coil|Coil]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Master
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Master
  - '[[SRD-Thousand Waves|Thousand Waves]]'
- - Master
  - '[[SRD-Thousand Arrows|Thousand Arrows]]'
- - Master
  - '[[SRD-Core Enforcer|Core Enforcer]]'
- - Master
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Master
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
Name: Zygarde 100%
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**DexID:** `= this.DexID`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
