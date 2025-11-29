---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Rounds: 4
    Type: WaterPledge
  TerrainEffect: WaterPledge
Attributes:
  Duration: 4
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon chants to invoke the power of water. Moisture in the\
  \ air bends the light to create a rainbow to bring good fortune. Everyone in the\
  \ field feels luckier for a while."
Effect: 'Area Move. This Effect Targets the Battlefield: Add 2 Dice to all Chance
  Dice rolls of everyone in the field. Duration 4 Rounds.'
Name: Water Pledge
Power: 3
Target: Area
Type: Water
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