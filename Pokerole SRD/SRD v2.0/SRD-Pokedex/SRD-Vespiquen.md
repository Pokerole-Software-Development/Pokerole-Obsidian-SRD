---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-vespiquen-BookSprite.png
BoxSprite: SRD-vespiquen-BoxSprite.png
DexCategory: Beehive Pokemon
DexDescription: "This Pokemon is female only. It raises grubs in the holes in its\
  \ body and secretes pheromones to control Combee to fight and gather honey for her.\
  \ It is a royal Pokemon that won\u2019t take orders from anyone."
EventAbilities: ''
Evolutions:
- Evolves: From
  Gender: Female
  Kind: Level
  Pokemon: '[[SRD-Combee]]'
  Speed: Slow
GenderType: F
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Unnerve
HomeSprite: SRD-vespiquen-HomeSprite.png
Image: vespiquen.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Starter
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Amateur
  - '[[SRD-Attack Order|Attack Order]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Defend Order|Defend Order]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Heal Order|Heal Order]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Ace
  - '[[SRD-Swagger|Swagger]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Ominous Wind|Ominous Wind]]'
Number: 416
ShuffleToken: SRD-vespiquen-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 38.5
  Pounds: 84.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vespiquen-BookSprite.png|wsmall]]
> ![[SRD-vespiquen-HomeSprite.png]]
> ![[SRD-vespiquen-BoxSprite.png|htiny]]
> ![[SRD-vespiquen-ShuffleToken.png|wsmall]]


*Beehive Pokemon*
*This Pokemon is female only. It raises grubs in the holes in its body and secretes pheromones to control Combee to fight and gather honey for her. It is a royal Pokemon that won’t take orders from anyone.*

**DexID**:: 0416
**Name**:: Vespiquen
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'9" / 1.2m
**Weight**: 84.9lbs / 38.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Speed   | Gender   |
|:----------|:---------------|:-------|:--------|:---------|
| From      | [[SRD-Combee]] | Level  | Slow    | Female   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Vespiquen.md"
flatten moves as T
where file.path = this.file.path
```
