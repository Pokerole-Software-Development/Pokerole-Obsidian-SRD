---
Ability1: Battle Armor
Ability2: ''
BookSprite: SRD-armaldo-BookSprite.png
BoxSprite: SRD-armaldo-BoxSprite.png
DexCategory: Plate Pokemon
DexDescription: When the waters receded, this Pokemon was forced to evolve to live
  on land. Evidence suggests that its claws could extend to reach the prey that was
  far or underwater. Its tough shell made it very resilient.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Anorith]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Swift Swim
HomeSprite: SRD-armaldo-HomeSprite.png
Image: armaldo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Sport|Mud Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Water Gun|Water Gun]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crush Claw|Crush Claw]]'
- - Ace
  - '[[SRD-Smack Down|Smack Down]]'
- - Ace
  - '[[SRD-Brine|Brine]]'
- - Ace
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Cross Poison|Cross Poison]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
Number: 348
ShuffleToken: SRD-armaldo-ShuffleToken.png
Type1: Rock
Type2: Bug
Weight:
  Kilograms: 68.2
  Pounds: 150.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-armaldo-BookSprite.png|wsmall]]
> ![[SRD-armaldo-HomeSprite.png]]
> ![[SRD-armaldo-BoxSprite.png|htiny]]
> ![[SRD-armaldo-ShuffleToken.png|wsmall]]


*Plate Pokemon*
*When the waters receded, this Pokemon was forced to evolve to live on land. Evidence suggests that its claws could extend to reach the prey that was far or underwater. Its tough shell made it very resilient.*

**DexID**:: 0348
**Name**:: Armaldo
**Type**:: Rock / Bug
**Abilities**:: [[SRD-Battle Armor|Battle Armor]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 150.4lbs / 68.2kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Anorith]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Armaldo.md"
flatten moves as T
where file.path = this.file.path
```
