---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Paralyze
Attributes:
  Charge: true
  Vulnerable: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon jumps at least 30 feet in the air before landing with\
  \ a mighty stomp on top of the foe. While in the air it is safe from most treaths\
  \ but its still vulnerable to bad weather."
Effect: 'Single Target. Charge Move. Out of Range while Charging. Vulnerable while
  charging to: Thunder / Twister / Sky Uppercut / Gust / Hurricane / Smack Down. Roll
  3 Chance Dice to Paralyze the Target.'
Name: Bounce
Power: 3
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