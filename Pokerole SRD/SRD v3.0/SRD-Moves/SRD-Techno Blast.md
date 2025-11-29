---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: "A laser briefly beams away from the Pok\xE9mon, whatever it hits explodes\
  \ a second later. This move can be modified with the right programing of a computer."
Effect: 'Single Target. Lethal. *If Genesect is performing this Move, this Move''s
  type may change to: Fire, Ice, Water, or Electric depending on the Driver it has
  as Held Item.'
Name: Techno Blast
Power: 5
Target: Foe
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