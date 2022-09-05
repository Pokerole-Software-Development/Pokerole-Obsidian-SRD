---
Accuracy1: Dexterity
Accuracy2: Channel
Damage1: Strength
Damage2: ''
Description: A blazing pillar of rainbow-colored flames crashes upon the foe, it burns
  and cleanses the evil from within. Those with a pure heart should not fear for they'll
  be unharmed.
DmgType: Physical
Effect: Lethal. Roll 5 Chance Dice to Apply Burn 3 to the Foe.
Name: Sacred Fire
Power: 4
Target: Foe
Type: Fire
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`