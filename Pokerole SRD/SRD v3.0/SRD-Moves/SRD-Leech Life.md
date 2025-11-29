---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects:
  Heal:
    Percentage: 0.5
    Target: User
    Type: Leech
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon clings to their foe, then bites in and starts to suck\
  \ away its life force."
Effect: Single Target. The User restores HP equal to half the damage dealt, rounded
  down.
Name: Leech Life
Power: 3
Target: Foe
Type: Bug
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