---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-rowlet-BookSprite.png
BoxSprite: SRD-rowlet-BoxSprite.png
DexCategory: Grass Quill Pokemon
DexDescription: "This is a shy Pokemon, it sleeps during the day, absorbing sunlight\
  \ through its feathers, then at night becomes more active. It likes to keep sight\
  \ of its trainer at all times, rotating its head 180\xB0 to do so."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dartrix]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Long Reach
HomeSprite: SRD-rowlet-HomeSprite.png
Image: rowlet.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leafage|Leafage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Foresight|Foresight]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Ace
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Curse|Curse]]'
- - Pro
  - '[[SRD-Haze|Haze]]'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
Number: 722
ShuffleToken: SRD-rowlet-ShuffleToken.png
Type1: Grass
Type2: Flying
Weight:
  Kilograms: 1.5
  Pounds: 3.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rowlet-BookSprite.png|wsmall]]
> ![[SRD-rowlet-HomeSprite.png]]
> ![[SRD-rowlet-BoxSprite.png|htiny]]
> ![[SRD-rowlet-ShuffleToken.png|wsmall]]


*Grass Quill Pokemon*
*This is a shy Pokemon, it sleeps during the day, absorbing sunlight through its feathers, then at night becomes more active. It likes to keep sight of its trainer at all times, rotating its head 180° to do so.*

**DexID**:: 0722
**Name**:: Rowlet
**Type**:: Grass / Flying
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Long Reach|Long Reach]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 3.3lbs / 1.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Dartrix]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Rowlet.md"
flatten moves as T
where file.path = this.file.path
```
