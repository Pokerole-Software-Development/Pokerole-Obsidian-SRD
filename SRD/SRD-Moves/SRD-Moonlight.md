---
Accuracy1: INSIGHT
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: The user gathers power from the light of the moon, the energy absorbed
  can heal most injuries.
DmgType: SUPPORT
Effect: Basic Heal. If successful spend 1 Will point to activate. If performed at
  Night or Sunny Weather is in effect this move becomes a Complete Heal. If Rain/Sandstorm
  Weather is in effect this move only heals 1 HP
Name: Moonlight
Power: 0
Target: User
Type: Fairy
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