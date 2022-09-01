---
Accuracy1: SPECIAL
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: The user manifests its mental power on the world, creating walls and
  floors of light that help prevent the passing of energies.
DmgType: SUPPORT
Effect: User and Allies will receive 1 less Damage from Special Attacks. Lasts 4 Rounds.
Name: Light Screen
Power: 0
Target: User and Allies
Type: Psychic
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`