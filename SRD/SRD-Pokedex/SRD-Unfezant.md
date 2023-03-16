---
Ability1: Big Pecks
Ability2: Super Luck
BookSprite: SRD-unfezant-BookSprite.png
BoxSprite: SRD-unfezant-BoxSprite.png
DexCategory: Proud Pokemon
DexDescription: Males swing the beautiful plumage on their heads to threaten others
  and to court females. Although less visually appealing, females are better at flying.
  Once they form a pair they are mated for life.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Tranquill]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Rivalry
HomeSprite: SRD-unfezant-HomeSprite.png
Image: unfezant.png
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
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
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
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Lucky Chant|Lucky Chant]]'
Number: 521
ShuffleToken: SRD-unfezant-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 29.0
  Pounds: 63.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-unfezant-BookSprite.png|wsmall]]
> ![[SRD-unfezant-HomeSprite.png]]
> ![[SRD-unfezant-BoxSprite.png|htiny]]
> ![[SRD-unfezant-ShuffleToken.png|wsmall]]


*Proud Pokemon*
*Males swing the beautiful plumage on their heads to threaten others and to court females. Although less visually appealing, females are better at flying. Once they form a pair they are mated for life.*

**DexID**:: 0521
**Name**:: Unfezant
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Big Pecks|Big Pecks]] / [[SRD-Super Luck|Super Luck]] ([[SRD-Rivalry|Rivalry]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 63.9lbs / 29.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Tranquill]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Unfezant.md"
flatten moves as T
where file.path = this.file.path
```
