---
Ability1: Swift Swim
Ability2: ''
BookSprite: SRD-floatzel-BookSprite.png
BoxSprite: SRD-floatzel-BoxSprite.png
DexCategory: Sea Weasel Pokemon
DexDescription: It floats using its well-developed sack. They roam close to fishing
  spots to steal an easy meal. People allow them to hang around their boats because
  they help whenever a person falls into the water.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Buizel]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Water Veil
HomeSprite: SRD-floatzel-HomeSprite.png
Image: floatzel.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Sonic Boom|Sonic Boom]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Ice Fang|Ice Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[SRD-Water Gun|Water Gun]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-Whirlpool|Whirlpool]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
Number: 419
ShuffleToken: SRD-floatzel-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 33.5
  Pounds: 73.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-floatzel-BookSprite.png|wsmall]]
> ![[SRD-floatzel-HomeSprite.png]]
> ![[SRD-floatzel-BoxSprite.png|htiny]]
> ![[SRD-floatzel-ShuffleToken.png|wsmall]]


*Sea Weasel Pokemon*
*It floats using its well-developed sack. They roam close to fishing spots to steal an easy meal. People allow them to hang around their boats because they help whenever a person falls into the water.*

**DexID**:: 0419
**Name**:: Floatzel
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] ([[SRD-Water Veil|Water Veil]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 73.9lbs / 33.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Buizel]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Floatzel.md"
flatten moves as T
where file.path = this.file.path
```
