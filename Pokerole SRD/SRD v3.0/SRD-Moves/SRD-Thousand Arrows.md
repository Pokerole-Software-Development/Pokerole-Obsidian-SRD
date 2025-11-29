---
Accuracy1: Strength
Accuracy2: Channel/Stealth
AddedEffects: {}
Attributes:
  Duration: wholeScene
  Lethal: true
  PhysicalRanged: true
  Ranged: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: Out of nowhere, pointy shards come raining from the sky towards the foes.
  Even flying creatures will fall to the ground if they are knocked by them. Take
  cover, this is gonna hurt.
Effect: Target All Foes in Range. Ranged. Lethal. Unique. Ignore the Target's immunity
  to Ground. Remove the immunity to Ground-Type Moves of those affected. Whole Scene
  Duration.
Name: Thousand Arrows
Power: 3
Target: All Foes
Type: Ground
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