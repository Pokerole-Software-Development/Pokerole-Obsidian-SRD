---
Accuracy1: Vitality
Accuracy2: Nature/Channel
AddedEffects:
  Heal:
    Percentage: 0.5
    Target: Targets
    Type: Leech
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon drains most of the foe\u2019s vital energy and feeds\
  \ on the nutrients it managed to extract."
Effect: Single Target. The User restores HP equal to half the damage dealt, rounded
  down.
Name: Giga Drain
Power: 3
Target: Foe
Type: Grass
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