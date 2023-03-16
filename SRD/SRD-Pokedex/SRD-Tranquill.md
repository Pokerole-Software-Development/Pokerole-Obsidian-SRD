---
Ability1: Big Pecks
Ability2: Super Luck
BookSprite: SRD-tranquill-BookSprite.png
BoxSprite: SRD-tranquill-BoxSprite.png
DexCategory: Wild Pigeon Pokemon
DexDescription: "During war and old times people made use of Tranquil\u2019s sense\
  \ of location to send letters. It will never fail to find it\u2019s way back home.\
  \ They like quiet forests and enjoy to relax in the peace and quiet."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Pidove]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Unfezant]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Rivalry
HomeSprite: SRD-tranquill-HomeSprite.png
Image: tranquill.png
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
Number: 520
ShuffleToken: SRD-tranquill-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 15.0
  Pounds: 33.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tranquill-BookSprite.png|wsmall]]
> ![[SRD-tranquill-HomeSprite.png]]
> ![[SRD-tranquill-BoxSprite.png|htiny]]
> ![[SRD-tranquill-ShuffleToken.png|wsmall]]


*Wild Pigeon Pokemon*
*During war and old times people made use of Tranquil’s sense of location to send letters. It will never fail to find it’s way back home. They like quiet forests and enjoy to relax in the peace and quiet.*

**DexID**:: 0520
**Name**:: Tranquill
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Big Pecks|Big Pecks]] / [[SRD-Super Luck|Super Luck]] ([[SRD-Rivalry|Rivalry]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 33.1lbs / 15.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Pidove]]   | Level  | Medium  |
| To        | [[SRD-Unfezant]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Tranquill.md"
flatten moves as T
where file.path = this.file.path
```
