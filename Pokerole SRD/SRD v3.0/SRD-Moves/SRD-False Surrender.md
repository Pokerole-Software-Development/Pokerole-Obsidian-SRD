---
Accuracy1: Insight
Accuracy2: Charm/Stealth
AddedEffects: {}
Attributes:
  NeverMiss: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon bows down in defeat, begging for forgiveness; then backstabs\
  \ the guillible foe."
Effect: Single Target. Never Miss.
Name: False Surrender
Power: 3
Target: Foe
Type: Dark
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