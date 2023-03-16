---
Ability1: Emergency Exit
Ability2: ''
BookSprite: SRD-golisopod-BookSprite.png
BoxSprite: SRD-golisopod-BoxSprite.png
DexCategory: Hard Scale Pokemon
DexDescription: This Pokemon is a rare sight, for most Wimpods never evolve and when
  they do, Golisopod spend most of their lives in deep sea caves, meditating. It is
  extremely strong, its claws can tear through everything.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Wimpod]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: ''
HomeSprite: SRD-golisopod-HomeSprite.png
Image: golisopod.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-First Impression|First Impression]]'
- - Amateur
  - '[[SRD-Spite|Spite]]'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Razor Shell|Razor Shell]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Pro
  - '[[SRD-Aqua Jet|Aqua Jet]]'
Number: 768
ShuffleToken: SRD-golisopod-ShuffleToken.png
Type1: Bug
Type2: Water
Weight:
  Kilograms: 108.0
  Pounds: 238.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-golisopod-BookSprite.png|wsmall]]
> ![[SRD-golisopod-HomeSprite.png]]
> ![[SRD-golisopod-BoxSprite.png|htiny]]
> ![[SRD-golisopod-ShuffleToken.png|wsmall]]


*Hard Scale Pokemon*
*This Pokemon is a rare sight, for most Wimpods never evolve and when they do, Golisopod spend most of their lives in deep sea caves, meditating. It is extremely strong, its claws can tear through everything.*

**DexID**:: 0768
**Name**:: Golisopod
**Type**:: Bug / Water
**Abilities**:: [[SRD-Emergency Exit|Emergency Exit]]
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 238.1lbs / 108.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Wimpod]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Golisopod.md"
flatten moves as T
where file.path = this.file.path
```
