---
Accuracy1: Clever
Accuracy2: Etiquette
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon signals the referee for half-time, the referee complies and
  both parties swap their sides of the field. Wait. Did we forget something?
Effect: Swap any Barriers (i.e.Light Screen, Reflect etc.), Entry Hazards (i.e. Toxic
  Spikes, Sticky Web etc.) and Effects on the foe's side of the field (i.e. Tailwind,
  Grassy Terrain etc.) for the one's on the User's side.
Name: Court Change
Power: 0
Target: Battlefield
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