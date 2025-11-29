---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects:
  TerrainEffect: ToxicSpikes
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon lays a trap of tiny venom-drenched spikes through the\
  \ battlefield. The battle has not yet begun and the foes are already defeated."
Effect: Target Foe's side of the Field. Entry Hazard. Foes who enter the battlefield
  become Poisoned. Roll 1 Chance Die for them to become Badly Poisoned instead. Pokemon
  with immunity to Ground-Type Moves are not affected.
Name: Toxic Spikes
Power: 0
Target: Foe's Battlefield
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