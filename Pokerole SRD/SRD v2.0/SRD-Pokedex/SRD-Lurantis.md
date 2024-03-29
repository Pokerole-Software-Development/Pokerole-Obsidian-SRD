---
Ability1: Leaf Guard
Ability2: ''
BookSprite: SRD-lurantis-BookSprite.png
BoxSprite: SRD-lurantis-BoxSprite.png
DexCategory: Bloom Sickle Pokemon
DexDescription: "Considered to be one of the mos beautiful Grass Pokemon due to its\
  \ lovely coloration. They require a lot of maintenance and constant grooming, so\
  \ they\u2019ll only trust a Trainer who is up to the job."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Fomantis]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Contrary
HomeSprite: SRD-lurantis-HomeSprite.png
Image: lurantis.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Cutter|Fury Cutter]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leafage|Leafage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Razor Leaf|Razor Leaf]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slash|Slash]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leaf Blade|Leaf Blade]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Synthesis|Synthesis]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Petal Blizzard|Petal Blizzard]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Solar Blade|Solar Blade]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sunny Day|Sunny Day]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swords Dance|Swords Dance]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leaf Storm|Leaf Storm]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Brick Break|Brick Break]]'
Number: 754
ShuffleToken: SRD-lurantis-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 18.5
  Pounds: 40.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lurantis-BookSprite.png|wsmall]]
> ![[SRD-lurantis-HomeSprite.png]]
> ![[SRD-lurantis-BoxSprite.png|htiny]]
> ![[SRD-lurantis-ShuffleToken.png|wsmall]]


*Bloom Sickle Pokemon*
*Considered to be one of the mos beautiful Grass Pokemon due to its lovely coloration. They require a lot of maintenance and constant grooming, so they’ll only trust a Trainer who is up to the job.*

**DexID**:: 0754
**Name**:: Lurantis
**Type**:: Grass
**Abilities**:: [[SRD-Leaf Guard|Leaf Guard]] ([[SRD-Contrary|Contrary]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'0" / 0.9m
**Weight**: 40.8lbs / 18.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Fomantis]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Lurantis.md"
flatten moves as T
where file.path = this.file.path
```
