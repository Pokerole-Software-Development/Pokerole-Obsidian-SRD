---
Accuracy1: Cool/Beauty
Accuracy2: Etiquette
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon gathers everyone for a cup of delicious tea, not eating\
  \ a snack along with it would be a waste."
Effect: Area Move. Those Affected will eat their held berries and berries on their
  Trainer's Bag without gaining their effects. Outside of battle, it will diffuse
  violent intentions for a few minutes.
Name: Teatime
Power: 0
Target: Area
Type: Normal
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