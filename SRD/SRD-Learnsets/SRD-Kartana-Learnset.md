---
DexID: 0797
Moves:
- - Master
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[SRD-Defog|Defog]]'
- - Master
  - '[[SRD-Vacuum Wave|Vacuum Wave]]'
- - Master
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Master
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Master
  - '[[SRD-Cut|Cut]]'
- - Master
  - '[[SRD-False Swipe|False Swipe]]'
- - Master
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Master
  - '[[SRD-Synthesis|Synthesis]]'
- - Master
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Master
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[SRD-Night Slash|Night Slash]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Master
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Master
  - '[[SRD-Detect|Detect]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Master
  - '[[SRD-Guillotine|Guillotine]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Knock Off|Knock Off]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
Name: Kartana
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
