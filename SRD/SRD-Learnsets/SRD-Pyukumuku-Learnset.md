---
DexID: '0770'
Moves:
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Purify|Purify]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Amateur
  - '[[SRD-Pain Split|Pain Split]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Soak|Soak]]'
- - Ace
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Bestow|Bestow]]'
- - Pro
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
Name: Pyukumuku
Species: '[[SRD-Pyukumuku|Pyukumuku]]'
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
