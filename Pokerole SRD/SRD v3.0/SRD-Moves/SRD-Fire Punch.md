---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Burn2
Attributes:
  FistMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: A fist powered by the fiery spirit of combat, the heat of the battle
  lights of for real as the punch hits the foe right where it hurts!
Effect: Single Target. Fist Move. Roll 1 Chance Die to inflict 2nd Degree Burn on
  the Target.
Name: Fire Punch
Power: 3
Target: Foe
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