---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects:
  Ailments:
  - Affects: User
    Type: Fly
Attributes:
  Charge: true
  Vulnerable: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon uses an action to fly up high, to asses the best angle\
  \ to take a dive against the foe. Pok\xE9mon who know this Move can fly for long\
  \ periods of time without rest."
Effect: 'Single Target. Charge Move. Out of Range while Charging. Vulnerable while
  charging to: Thunder / Twister / Sky Uppercut / Gust / Hurricane / Smack Down. Out
  of battle allows the Pokemon to fly long distances.'
Name: Fly
Power: 4
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