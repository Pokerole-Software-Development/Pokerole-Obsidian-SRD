---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Grounded
Attributes:
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "They say it\u2019s great to get two birds with one stone, this Pok\xE9\
  mon will give one bird ALL the stones."
Effect: Single Target. Ranged. Remove the Target's immunity to Ground-Type Moves.
  If the Target is Out of Range due to using "Fly", "Bounce" or "Sky Drop", this Move
  hits anyways.
Name: Smack Down
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