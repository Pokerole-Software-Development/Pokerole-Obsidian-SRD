---
Accuracy1: Strength
Accuracy2: Intimidate
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon throws a tantrum and stomps all over the place, it becomes\
  \ worse if something has previously frustrated them."
Effect: Single Target. *Add 2 Extra Dice to the Damage Pool of this Move if the User
  failed the Accuracy roll of the last Move it performed. If the Target is out of
  range due to using the Move "Dig", this Move hits anyways.
Name: Stomping Tantrum
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