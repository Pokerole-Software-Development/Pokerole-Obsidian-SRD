---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -2
  CutterMove: true
  Duration: 4
  HighCritical: true
  OngoingDamage: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon hacks at the foe with a furious stone axe. Pointy pebbles\
  \ and rubble remain within the cut, making the foe start limping."
Effect: Single Target. Low Accuracy 2. High Critical. Cutter Move. Ongoing Damage.
  Duration 4 Rounds.
Name: Stone Axe
Power: 2
Target: Foe
Type: Rock
---

#PokeroleSRD/Moves

### `= this.name`
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`