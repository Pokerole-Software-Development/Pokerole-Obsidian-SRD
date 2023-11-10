---
Ability1: Sand Rush
Ability2: Sand Force
BookSprite: SRD-excadrill-BookSprite.png
BoxSprite: SRD-excadrill-BoxSprite.png
DexCategory: Subterrene Pokemon
DexDescription: They build maze-like nests deep underground. Humans make use of their
  drilling abilities to dig tunnels for subway trains. This Pokemon does not back
  out from foes and can be a formidable opponent.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Drilbur]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Mold Breaker
HomeSprite: SRD-excadrill-HomeSprite.png
Image: excadrill.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Amateur
  - '[[SRD-Horn Drill|Horn Drill]]'
- - Amateur
  - '[[SRD-Rototiller|Rototiller]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Drill Run|Drill Run]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Smart Strike|Smart Strike]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
Number: 530
ShuffleToken: SRD-excadrill-ShuffleToken.png
Type1: Ground
Type2: Steel
Weight:
  Kilograms: 40.4
  Pounds: 89.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-excadrill-BookSprite.png|wsmall]]
> ![[SRD-excadrill-HomeSprite.png]]
> ![[SRD-excadrill-BoxSprite.png|htiny]]
> ![[SRD-excadrill-ShuffleToken.png|wsmall]]


*Subterrene Pokemon*
*They build maze-like nests deep underground. Humans make use of their drilling abilities to dig tunnels for subway trains. This Pokemon does not back out from foes and can be a formidable opponent.*

**DexID**:: 0530
**Name**:: Excadrill
**Type**:: Ground / Steel
**Abilities**:: [[SRD-Sand Rush|Sand Rush]] / [[SRD-Sand Force|Sand Force]] ([[SRD-Mold Breaker|Mold Breaker]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 89.1lbs / 40.4kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Drilbur]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Excadrill.md"
flatten moves as T
where file.path = this.file.path
```
