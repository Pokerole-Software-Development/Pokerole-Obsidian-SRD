---
Ability1: Sand Veil
Ability2: Arena Trap
BookSprite: SRD-diglett-BookSprite.png
BoxSprite: SRD-diglett-BoxSprite.png
DexCategory: Mole Pokemon
DexDescription: "It prefers dark places and spends most of its time underground. It\
  \ has a very thin skin. It\u2019s frail and has problems regulating its own temperature.\
  \ Keep it burrowed or it will get sick."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dugtrio]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Sand Force
HomeSprite: SRD-diglett-HomeSprite.png
Image: diglett.png
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
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Earth Power|Earth Power]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Screech|Screech]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Feint Attack|Feint Attack]]'
Number: 50
ShuffleToken: SRD-diglett-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 0.8
  Pounds: 1.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-diglett-BookSprite.png|wsmall]]
> ![[SRD-diglett-HomeSprite.png]]
> ![[SRD-diglett-BoxSprite.png|htiny]]
> ![[SRD-diglett-ShuffleToken.png|wsmall]]


*Mole Pokemon*
*It prefers dark places and spends most of its time underground. It has a very thin skin. It’s frail and has problems regulating its own temperature. Keep it burrowed or it will get sick.*

**DexID**:: 0050
**Name**:: Diglett
**Type**:: Ground
**Abilities**:: [[SRD-Sand Veil|Sand Veil]] / [[SRD-Arena Trap|Arena Trap]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 0'7" / 0.2m
**Weight**: 1.8lbs / 0.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Dugtrio]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Diglett.md"
flatten moves as T
where file.path = this.file.path
```
