---
Ability1: Sand Veil
Ability2: Arena Trap
BookSprite: SRD-dugtrio-BookSprite.png
BoxSprite: SRD-dugtrio-BoxSprite.png
DexCategory: Mole Pokemon
DexDescription: Because the triplets originally split from one body, they think exactly
  alike. They work together to dig endlessly through the ground. They are known for
  destroying the foundations of roads and buildings.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Diglett]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Sand Force
HomeSprite: SRD-dugtrio-HomeSprite.png
Image: dugtrio.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Magnitude|Magnitude]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Earth Power|Earth Power]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Rototiller|Rototiller]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Tri Attack|Tri Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Pro
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
Number: 51
ShuffleToken: SRD-dugtrio-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 33.3
  Pounds: 73.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dugtrio-BookSprite.png|wsmall]]
> ![[SRD-dugtrio-HomeSprite.png]]
> ![[SRD-dugtrio-BoxSprite.png|htiny]]
> ![[SRD-dugtrio-ShuffleToken.png|wsmall]]


*Mole Pokemon*
*Because the triplets originally split from one body, they think exactly alike. They work together to dig endlessly through the ground. They are known for destroying the foundations of roads and buildings.*

**DexID**:: 0051
**Name**:: Dugtrio
**Type**:: Ground
**Abilities**:: [[SRD-Sand Veil|Sand Veil]] / [[SRD-Arena Trap|Arena Trap]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 73.4lbs / 33.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Diglett]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dugtrio.md"
flatten moves as T
where file.path = this.file.path
```
