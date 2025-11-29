---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  HighCritical: true
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon uses their ghostly claws to slash through their foe\u2019\
  s body tearing not their flesh but their soul directly."
Effect: Single Target. Lethal. High Critical.
Name: Shadow Claw
Power: 3
Target: Foe
Type: Ghost
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