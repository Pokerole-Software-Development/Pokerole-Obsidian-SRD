---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  IgnoreShield: true
Attributes:
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: You suddenly stop your in tracks as you see a bright and blinding light
  coming towards you at great speed. You did not see what hit you and then it's all
  darkness.
Effect: Lethal. If anything on the foe's side of the field would prevent this move
  from dealing damage (Pokemon types. Abilities. Shield Moves. Weather. Or Barriers.)
  ignore it. This Move cannot be Clashed.
Name: Sunsteel Strike
Power: 4
Target: Foe
Type: Steel
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