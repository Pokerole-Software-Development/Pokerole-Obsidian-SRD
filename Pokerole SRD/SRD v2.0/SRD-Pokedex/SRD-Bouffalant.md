---
Ability1: Reckless
Ability2: Sap Sipper
BookSprite: SRD-bouffalant-BookSprite.png
BoxSprite: SRD-bouffalant-BoxSprite.png
DexCategory: Bash Buffalo Pokemon
DexDescription: They form herds on the coldest plains. They bash and headbutt to attack
  their foes. The fluffy fur on their heads absorbs damage to their skulls. Years
  ago, a Bouffalant derailed a train with a bash.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Soundproof
HomeSprite: SRD-bouffalant-HomeSprite.png
Image: bouffalant.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pursuit|Pursuit]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rage|Rage]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Attack|Fury Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Horn Attack|Horn Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Revenge|Revenge]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Head Charge|Head Charge]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Reversal|Reversal]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Megahorn|Megahorn]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thrash|Thrash]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Skull Bash|Skull Bash]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
Number: 626
ShuffleToken: SRD-bouffalant-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 94.6
  Pounds: 208.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bouffalant-BookSprite.png|wsmall]]
> ![[SRD-bouffalant-HomeSprite.png]]
> ![[SRD-bouffalant-BoxSprite.png|htiny]]
> ![[SRD-bouffalant-ShuffleToken.png|wsmall]]


*Bash Buffalo Pokemon*
*They form herds on the coldest plains. They bash and headbutt to attack their foes. The fluffy fur on their heads absorbs damage to their skulls. Years ago, a Bouffalant derailed a train with a bash.*

**DexID**:: 0626
**Name**:: Bouffalant
**Type**:: Normal
**Abilities**:: [[SRD-Reckless|Reckless]] / [[SRD-Sap Sipper|Sap Sipper]] ([[SRD-Soundproof|Soundproof]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 208.6lbs / 94.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Bouffalant.md"
flatten moves as T
where file.path = this.file.path
```
