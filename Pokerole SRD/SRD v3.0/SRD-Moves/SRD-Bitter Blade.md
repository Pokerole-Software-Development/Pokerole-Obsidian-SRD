---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Heal:
    Percentage: 0.5
    Target: User
    Type: Leech
Attributes:
  CutterMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user focuses its bitter feelings towards the world of the living
  into a slashing attack, seeing the suffering it brings to others makes it feel reinvigorated.
Effect: Single Target. Cutter Move. The User restores HP equal to half the damage
  dealt, rounded down.
Name: Bitter Blade
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