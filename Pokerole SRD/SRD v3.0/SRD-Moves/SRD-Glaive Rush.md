---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user attacks with its sharp dorsal fin by doing a somersault slash.
  This can pretty much slice in half anything, but it also leaves the user prone to
  sneak attacks.
Effect: 'Single Target. Lethal. The User is now Vulnerable to: The Next Physical or
  Special Move that targets them.'
Name: Glaive Rush
Power: 6
Target: Foe
Type: Dragon
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