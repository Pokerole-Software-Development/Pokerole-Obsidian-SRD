---
Ability1: Cheek Pouch
Ability2: Pickup
BookSprite: SRD-dedenne-BookSprite.png
BoxSprite: SRD-dedenne-BoxSprite.png
DexCategory: Antenna Pokemon
DexDescription: The tail is used to absorb electricity from power outlets. They communicate
  with each other by feeling the static on their whiskers. Its cute and cuddly appearance
  make it a favorite pet.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Plus
HomeSprite: SRD-dedenne-HomeSprite.png
Image: dedenne.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Shock|Thunder Shock]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charm|Charm]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Parabolic Charge|Parabolic Charge]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nuzzle|Nuzzle]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Volt Switch|Volt Switch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rest|Rest]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Snore|Snore]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge Beam|Charge Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Entrainment|Entrainment]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder|Thunder]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Discharge|Discharge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Super Fang|Super Fang]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Tail|Iron Tail]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Eerie Impulse|Eerie Impulse]]'
Number: 702
ShuffleToken: SRD-dedenne-ShuffleToken.png
Type1: Electric
Type2: Fairy
Weight:
  Kilograms: 2.2
  Pounds: 4.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dedenne-BookSprite.png|wsmall]]
> ![[SRD-dedenne-HomeSprite.png]]
> ![[SRD-dedenne-BoxSprite.png|htiny]]
> ![[SRD-dedenne-ShuffleToken.png|wsmall]]


*Antenna Pokemon*
*The tail is used to absorb electricity from power outlets. They communicate with each other by feeling the static on their whiskers. Its cute and cuddly appearance make it a favorite pet.*

**DexID**:: 0702
**Name**:: Dedenne
**Type**:: Electric / Fairy
**Abilities**:: [[SRD-Cheek Pouch|Cheek Pouch]] / [[SRD-Pickup|Pickup]] ([[SRD-Plus|Plus]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 0'7" / 0.2m
**Weight**: 4.9lbs / 2.2kg
**Good Starter**:: No
**Recommended Rank**:: Starter

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dedenne.md"
flatten moves as T
where file.path = this.file.path
```
