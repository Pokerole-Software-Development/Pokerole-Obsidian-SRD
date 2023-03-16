---
Ability1: Immunity
Ability2: ''
BookSprite: SRD-zangoose-BookSprite.png
BoxSprite: SRD-zangoose-BoxSprite.png
DexCategory: Cat Ferret Pokemon
DexDescription: The sole desire to battle Sevipers is embedded in their genes, they
  have been rivals since forever. Zangoose is a very agile quadruped, standing up
  on two legs only when ready to fight.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Toxic Boost
HomeSprite: SRD-zangoose-HomeSprite.png
Image: zangoose.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Crush Claw|Crush Claw]]'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Detect|Detect]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Taunt|Taunt]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Pro
  - '[[SRD-Metal Claw|Metal Claw]]'
Number: 335
ShuffleToken: SRD-zangoose-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 40.3
  Pounds: 88.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zangoose-BookSprite.png|wsmall]]
> ![[SRD-zangoose-HomeSprite.png]]
> ![[SRD-zangoose-BoxSprite.png|htiny]]
> ![[SRD-zangoose-ShuffleToken.png|wsmall]]


*Cat Ferret Pokemon*
*The sole desire to battle Sevipers is embedded in their genes, they have been rivals since forever. Zangoose is a very agile quadruped, standing up on two legs only when ready to fight.*

**DexID**:: 0335
**Name**:: Zangoose
**Type**:: Normal
**Abilities**:: [[SRD-Immunity|Immunity]] ([[SRD-Toxic Boost|Toxic Boost]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'3" / 1.3m
**Weight**: 88.8lbs / 40.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Zangoose.md"
flatten moves as T
where file.path = this.file.path
```
