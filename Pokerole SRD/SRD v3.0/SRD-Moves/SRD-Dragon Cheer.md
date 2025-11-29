---
Accuracy1: Tough
Accuracy2: Charm
AddedEffects: {}
Attributes:
  HighCritical: true
Category: Support
Damage1: ''
Damage2: ''
Description: "With a mighty roar, the Pok\xE9mon fires up the battle spirit of their\
  \ companions on their quest for victory."
Effect: Target Allies in Range. All Physical and Special Moves of the Allies now have
  the "High Critical" Added Effect. *If an Ally is a Dragon-Type, Increase their Strength
  and Special by 1.
Name: Dragon Cheer
Power: 0
Target: ''
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