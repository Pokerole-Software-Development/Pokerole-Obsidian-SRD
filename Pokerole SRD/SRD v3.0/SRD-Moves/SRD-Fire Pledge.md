---
Accuracy1: Insight
Accuracy2: Intimidate
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon chants to invoke the power of fire, their pledge is heard\
  \ and the flames come forward to aid them in battle."
Effect: 'Area Move. This Effect Targets the Battle Field: At the End of the Round,
  Roll 2 Dice of Fire-Type Damage to everyone without immunity to Ground on the field
  ignoring defenses. Duration 4 Rounds.'
Name: Fire Pledge
Power: 3
Target: Area
Type: Fire
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