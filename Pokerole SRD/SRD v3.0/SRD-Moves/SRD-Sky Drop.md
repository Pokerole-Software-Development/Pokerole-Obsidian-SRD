---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Charge: true
  Vulnerable: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon clutches their foe and starts flying up high, then drops\
  \ the foe from a decent altitude. Let gravity handle this one."
Effect: 'Single Target. Charge Move. Out of Range while Charging. Vulnerable while
  charging to: Thunder / Twister / Sky Uppercut / Gust / Hurricane / Smack Down. Flinch
  Target. If Target is Flying-Type or too heavy to carry, this Move fails. See Strength
  chart on p. 532.'
Name: Sky Drop
Power: 2
Target: Foe
Type: Flying
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