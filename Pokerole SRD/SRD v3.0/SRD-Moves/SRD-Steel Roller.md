---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Lethal: true
  ResetTerrain: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon rolls into a wheel, destroying anything in their path.\
  \ Buildings come crashing down, forests are swept away and the soil is left as a\
  \ blank slate."
Effect: Single Target. Lethal. Can't be used if there is no Active Terrain (Grassy
  Terrain, Electric Terrain, etc.) on the Battlefield. Remove any active Terrain on
  the Battlefield.
Name: Steel Roller
Power: 5
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