---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: LightScreen
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user manifests its mental power on the world, creating walls and
  floors of light that help prevent the passing of energies.
Effect: User and Allies will receive 1 less Damage from Special Attacks. Lasts 4 Rounds.
Name: Light Screen
Power: 0
Target: User and Allies
Type: Psychic
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