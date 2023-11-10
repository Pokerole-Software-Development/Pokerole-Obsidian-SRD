---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-grovyle-BookSprite.png
BoxSprite: SRD-grovyle-BoxSprite.png
DexCategory: Wood Gecko Pokemon
DexDescription: "Their leaves provide camouflage in the jungles. They appear to fly\
  \ from tree to tree, jumping huge lengths with amazing speed. It\u2019s almost impossible\
  \ to catch them once they start running away.."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Treecko]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Sceptile]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Unburden
HomeSprite: SRD-grovyle-HomeSprite.png
Image: grovyle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Ace
  - '[[SRD-Detect|Detect]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
Number: 253
ShuffleToken: SRD-grovyle-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 21.6
  Pounds: 47.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-grovyle-BookSprite.png|wsmall]]
> ![[SRD-grovyle-HomeSprite.png]]
> ![[SRD-grovyle-BoxSprite.png|htiny]]
> ![[SRD-grovyle-ShuffleToken.png|wsmall]]


*Wood Gecko Pokemon*
*Their leaves provide camouflage in the jungles. They appear to fly from tree to tree, jumping huge lengths with amazing speed. It’s almost impossible to catch them once they start running away..*

**DexID**:: 0253
**Name**:: Grovyle
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Unburden|Unburden]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 47.6lbs / 21.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Treecko]]  | Level  | Medium  |
| To        | [[SRD-Sceptile]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Grovyle.md"
flatten moves as T
where file.path = this.file.path
```
