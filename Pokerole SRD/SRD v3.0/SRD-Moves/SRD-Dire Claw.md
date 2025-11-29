---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Poison
  - Affects: Targets
    ChanceDice: 2
    Type: Paralyze
  - Affects: Targets
    ChanceDice: 2
    Type: Sleep
Attributes:
  HighCritical: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon makes a cut on their victim with claws drenched in venom;\
  \ then patiently stalks it, waiting for the toxins to wear it out."
Effect: Single Target. High Critical. Roll 2 Chance Dice to Poison the Target. Roll
  2 Chance Dice to Paralyze the Target. Roll 2 Chance Dice to put the Target to Sleep.
Name: Dire Claw
Power: 3
Target: Foe
Type: Poison
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