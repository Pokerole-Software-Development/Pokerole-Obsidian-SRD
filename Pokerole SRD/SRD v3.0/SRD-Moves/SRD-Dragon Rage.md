---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  FixedDamage:
    Target: Targets
    Type: Absolute
    Value: 2
Attributes: {}
Category: Special
Damage1: SetDamage
Damage2: ''
Description: "The Pok\xE9mon focuses their inner rage and makes it not-soinner anymore."
Effect: Single Target. Set Damage. Deal 2 Dragon-Type Damage to the Target.
Name: Dragon Rage
Power: 0
Target: Foe
Type: Dragon
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