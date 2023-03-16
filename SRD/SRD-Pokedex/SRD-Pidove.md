---
Ability1: Big Pecks
Ability2: Super Luck
BookSprite: SRD-pidove-BookSprite.png
BoxSprite: SRD-pidove-BoxSprite.png
DexCategory: Tiny Pigeon Pokemon
DexDescription: These Pokemon thrive in the cities. They are accustomed to people
  and they often gather in the parks. They are forgetful and not very smart, but they
  always remember the way back home.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Tranquill]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Rivalry
HomeSprite: SRD-pidove-HomeSprite.png
Image: pidove.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Gust|Gust]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Air Cutter|Air Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Detect|Detect]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[SRD-Feather Dance|Feather Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Swagger|Swagger]]'
- - Ace
  - '[[SRD-Facade|Facade]]'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - Ace
  - '[[SRD-Sky Attack|Sky Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Steel Wing|Steel Wing]]'
- - Pro
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Pro
  - '[[SRD-Hypnosis|Hypnosis]]'
Number: 519
ShuffleToken: SRD-pidove-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 2.1
  Pounds: 4.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pidove-BookSprite.png|wsmall]]
> ![[SRD-pidove-HomeSprite.png]]
> ![[SRD-pidove-BoxSprite.png|htiny]]
> ![[SRD-pidove-ShuffleToken.png|wsmall]]


*Tiny Pigeon Pokemon*
*These Pokemon thrive in the cities. They are accustomed to people and they often gather in the parks. They are forgetful and not very smart, but they always remember the way back home.*

**DexID**:: 0519
**Name**:: Pidove
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Big Pecks|Big Pecks]] / [[SRD-Super Luck|Super Luck]] ([[SRD-Rivalry|Rivalry]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 4.6lbs / 2.1kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Tranquill]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Pidove.md"
flatten moves as T
where file.path = this.file.path
```
