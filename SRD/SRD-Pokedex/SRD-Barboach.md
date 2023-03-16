---
Ability1: Oblivious
Ability2: Anticipation
BookSprite: SRD-barboach-BookSprite.png
BoxSprite: SRD-barboach-BoxSprite.png
DexCategory: Whiskers Pokemon
DexDescription: Their whiskers work as a super sensitive radar. They hide in the mud
  with only their whiskers exposed, waiting for prey to come. If the mud dries, they
  move back into the water.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Whiscash]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Hydration
HomeSprite: SRD-barboach-HomeSprite.png
Image: barboach.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Mud Slap|Mud Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Magnitude|Magnitude]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Snore|Snore]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dive|Dive]]'
- - Pro
  - '[[SRD-Flail|Flail]]'
- - Pro
  - '[[SRD-Mud Shot|Mud Shot]]'
Number: 339
ShuffleToken: SRD-barboach-ShuffleToken.png
Type1: Water
Type2: Ground
Weight:
  Kilograms: 1.9
  Pounds: 4.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-barboach-BookSprite.png|wsmall]]
> ![[SRD-barboach-HomeSprite.png]]
> ![[SRD-barboach-BoxSprite.png|htiny]]
> ![[SRD-barboach-ShuffleToken.png|wsmall]]


*Whiskers Pokemon*
*Their whiskers work as a super sensitive radar. They hide in the mud with only their whiskers exposed, waiting for prey to come. If the mud dries, they move back into the water.*

**DexID**:: 0339
**Name**:: Barboach
**Type**:: Water / Ground
**Abilities**:: [[SRD-Oblivious|Oblivious]] / [[SRD-Anticipation|Anticipation]] ([[SRD-Hydration|Hydration]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 4.2lbs / 1.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Whiscash]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Barboach.md"
flatten moves as T
where file.path = this.file.path
```
