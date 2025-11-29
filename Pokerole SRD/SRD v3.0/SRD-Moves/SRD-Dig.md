---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects:
  Ailments:
  - Affects: User
    Type: Dig
Attributes:
  Charge: true
  Vulnerable: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user digs a tunnel on the ground and attacks by coming out from below
  its target. This move has been used to escape caves and gain access to highly surveiled
  places.
Effect: 'Single Target. Charge Move. Out of Range while Charging. Vulnerable while
  charging to: Earth Power/ Earthquake/ Fissure/ Magnitude/ Stomping Tantrum. Out
  of battle allows the Pokemon to burrow and make underground tunnels.'
Name: Dig
Power: 3
Target: Foe
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