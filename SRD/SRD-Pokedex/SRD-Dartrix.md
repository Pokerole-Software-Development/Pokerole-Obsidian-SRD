---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-dartrix-BookSprite.png
BoxSprite: SRD-dartrix-BoxSprite.png
DexCategory: Blade Quill Pokemon
DexDescription: Dartix are vain creatures, they dislike it when their feathers are
  ruffled, even stopping midfight to groom them. Despite its elegant demeanor it hides
  an awkward personality, prone to panic and clumsiness.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Rowlet]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Decidueye]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Long Reach
HomeSprite: SRD-dartrix-HomeSprite.png
Image: dartrix.png
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
Number: 723
ShuffleToken: SRD-dartrix-ShuffleToken.png
Type1: Grass
Type2: Flying
Weight:
  Kilograms: 16.0
  Pounds: 35.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dartrix-BookSprite.png|wsmall]]
> ![[SRD-dartrix-HomeSprite.png]]
> ![[SRD-dartrix-BoxSprite.png|htiny]]
> ![[SRD-dartrix-ShuffleToken.png|wsmall]]


*Blade Quill Pokemon*
*Dartix are vain creatures, they dislike it when their feathers are ruffled, even stopping midfight to groom them. Despite its elegant demeanor it hides an awkward personality, prone to panic and clumsiness.*

**DexID**:: 0723
**Name**:: Dartrix
**Type**:: Grass / Flying
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Long Reach|Long Reach]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 35.3lbs / 16.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Rowlet]]    | Level  | Medium  |
| To        | [[SRD-Decidueye]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Dartrix.md"
flatten moves as T
where file.path = this.file.path
```
