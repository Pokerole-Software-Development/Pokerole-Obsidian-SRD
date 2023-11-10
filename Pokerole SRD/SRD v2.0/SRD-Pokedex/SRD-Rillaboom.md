---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-rillaboom-BookSprite.png
BoxSprite: SRD-rillaboom-BoxSprite.png
DexCategory: Drummer Pokemon
DexDescription: The leader owns the largest drum among its troop and has the best
  drumming technique which makes roots sprout to attack its foes. But they are peaceful
  and kind, creatures that value harmony in their group.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Thwackey]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: Grassy Surge
HomeSprite: SRD-rillaboom-HomeSprite.png
Image: rillaboom.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Drum Beating|Drum Beating]]'
- - Starter
  - '[[SRD-Double Hit|Double Hit]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Beginner
  - '[[SRD-Noble Roar|Noble Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Scratch|Scratch]]'
- - Amateur
  - '[[SRD-Growl|Growl]]'
- - Amateur
  - '[[SRD-Branch Poke|Branch Poke]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Knock Off|Knock Off]]'
- - Ace
  - '[[SRD-Slam|Slam]]'
- - Ace
  - '[[SRD-Uproar|Uproar]]'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - Ace
  - '[[SRD-Boomburst|Boomburst]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Growth|Growth]]'
- - Pro
  - '[[SRD-Nature Power|Nature Power]]'
- - Pro
  - '[[SRD-Frenzy Plant|Frenzy Plant]]'
Number: 812
ShuffleToken: SRD-rillaboom-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 90.0
  Pounds: 198.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rillaboom-BookSprite.png|wsmall]]
> ![[SRD-rillaboom-HomeSprite.png]]
> ![[SRD-rillaboom-BoxSprite.png|htiny]]
> ![[SRD-rillaboom-ShuffleToken.png|wsmall]]


*Drummer Pokemon*
*The leader owns the largest drum among its troop and has the best drumming technique which makes roots sprout to attack its foes. But they are peaceful and kind, creatures that value harmony in their group.*

**DexID**:: 0812
**Name**:: Rillaboom
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Grassy Surge|Grassy Surge]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 6'9" / 2.1m
**Weight**: 198.4lbs / 90.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Thwackey]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rillaboom.md"
flatten moves as T
where file.path = this.file.path
```
