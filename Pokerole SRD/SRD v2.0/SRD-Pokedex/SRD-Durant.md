---
Ability1: Swarm
Ability2: Hustle
BookSprite: SRD-durant-BookSprite.png
BoxSprite: SRD-durant-BoxSprite.png
DexCategory: Iron Ant Pokemon
DexDescription: Durant build complex mazes of tunnels in the mountains. Each colony
  has hundreds of Durant, all playing different roles in driving Heatmor away from
  their nest as it is their only predator.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Truant
HomeSprite: SRD-durant-HomeSprite.png
Image: durant.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Starter
  - '[[SRD-Vice Grip|Vice Grip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Screech|Screech]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 632
ShuffleToken: SRD-durant-ShuffleToken.png
Type1: Bug
Type2: Steel
Weight:
  Kilograms: 33.0
  Pounds: 72.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-durant-BookSprite.png|wsmall]]
> ![[SRD-durant-HomeSprite.png]]
> ![[SRD-durant-BoxSprite.png|htiny]]
> ![[SRD-durant-ShuffleToken.png|wsmall]]


*Iron Ant Pokemon*
*Durant build complex mazes of tunnels in the mountains. Each colony has hundreds of Durant, all playing different roles in driving Heatmor away from their nest as it is their only predator.*

**DexID**:: 0632
**Name**:: Durant
**Type**:: Bug / Steel
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Hustle|Hustle]] ([[SRD-Truant|Truant]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 72.8lbs / 33.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Durant.md"
flatten moves as T
where file.path = this.file.path
```
