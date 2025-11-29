---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  IgnoreShield: true
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Using their tail as a powerful drill, the Pok\xE9mon pierces through\
  \ any surface it comes in contact with."
Effect: Single Target. Lethal. Ignore Shield Moves active on the Foe or their side
  of the field.
Name: Hyper Drill
Power: 3
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