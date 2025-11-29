---
Accuracy1: Vitality
Accuracy2: Charm
AddedEffects:
  Heal:
    Percentage: 0.5
    Target: User
    Type: Leech
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon blows a flirtatious kiss; the foe catches it believing\
  \ to have found love, but it turns out to be a trick to steal its life energy."
Effect: Single Target. The User restores HP equal to half the damage dealt, rounded
  down.
Name: Draining Kiss
Power: 2
Target: Foe
Type: Fairy
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