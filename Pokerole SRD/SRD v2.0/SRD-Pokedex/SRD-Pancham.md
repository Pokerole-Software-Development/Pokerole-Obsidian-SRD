---
Ability1: Iron Fist
Ability2: Mold Breaker
BookSprite: SRD-pancham-BookSprite.png
BoxSprite: SRD-pancham-BoxSprite.png
DexCategory: Playful Pokemon
DexDescription: It lives in bamboo forests. It is very energetic and playful, but
  wants to be taken seriously. It has a hard time due to its cute appearance, for
  this reason it may start hanging out with the wrong crowd.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Pangoro]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Scrappy
HomeSprite: SRD-pancham-HomeSprite.png
Image: pancham.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Arm Thrust|Arm Thrust]]'
- - Beginner
  - '[[SRD-Work Up|Work Up]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Karate Chop|Karate Chop]]'
- - Amateur
  - '[[SRD-Comet Punch|Comet Punch]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Circle Throw|Circle Throw]]'
- - Amateur
  - '[[SRD-Vital Throw|Vital Throw]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - Ace
  - '[[SRD-Parting Shot|Parting Shot]]'
- - Ace
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
Number: 674
ShuffleToken: SRD-pancham-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 8.0
  Pounds: 17.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pancham-BookSprite.png|wsmall]]
> ![[SRD-pancham-HomeSprite.png]]
> ![[SRD-pancham-BoxSprite.png|htiny]]
> ![[SRD-pancham-ShuffleToken.png|wsmall]]


*Playful Pokemon*
*It lives in bamboo forests. It is very energetic and playful, but wants to be taken seriously. It has a hard time due to its cute appearance, for this reason it may start hanging out with the wrong crowd.*

**DexID**:: 0674
**Name**:: Pancham
**Type**:: Fighting
**Abilities**:: [[SRD-Iron Fist|Iron Fist]] / [[SRD-Mold Breaker|Mold Breaker]] ([[SRD-Scrappy|Scrappy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 17.6lbs / 8.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Pangoro]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pancham.md"
flatten moves as T
where file.path = this.file.path
```
