---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  BlockDamagePool: 2
  Duration: 4
  OngoingDamage: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon summons a bothersome swarm to prevent the foe from escaping.\
  \ The swarm will relentlessly attack the foe."
Effect: Single Target. Blocks. Ongoing Damage. Duration 4 Rounds. Increase the Target's
  difficulty to Evade at Storyteller's discretion.
Name: Infestation
Power: 1
Target: Foe
Type: Bug
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