---
DexID: '0200'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Psywave|Psywave]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Spite|Spite]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Pain Split|Pain Split]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
Name: Misdreavus
Species: '[[SRD-Misdreavus|Misdreavus]]'
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
