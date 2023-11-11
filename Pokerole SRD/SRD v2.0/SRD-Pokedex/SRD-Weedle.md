---
Ability1: Shield Dust
Ability2: ''
BookSprite: SRD-weedle-BookSprite.png
BoxSprite: SRD-weedle-BoxSprite.png
DexCategory: Hairy Pokemon
DexDescription: Often found in forests eating leaves. It has a sharp, venomous stinger
  on its head for defense. It has an acute sense of smell to find food, and its bright-colored
  body is intended to warn off predators.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Kakuna]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Run Away
HomeSprite: SRD-weedle-HomeSprite.png
Image: weedle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Sting|Poison Sting]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-String Shot|String Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Electroweb|Electroweb]]'
Number: 13
ShuffleToken: SRD-weedle-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 3.2
  Pounds: 7.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-weedle-BookSprite.png|wsmall]]
> ![[SRD-weedle-HomeSprite.png]]
> ![[SRD-weedle-BoxSprite.png|htiny]]
> ![[SRD-weedle-ShuffleToken.png|wsmall]]


*Hairy Pokemon*
*Often found in forests eating leaves. It has a sharp, venomous stinger on its head for defense. It has an acute sense of smell to find food, and its bright-colored body is intended to warn off predators.*

**DexID**:: 0013
**Name**:: Weedle
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Shield Dust|Shield Dust]] ([[SRD-Run Away|Run Away]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 7.1lbs / 3.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Kakuna]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Weedle.md"
flatten moves as T
where file.path = this.file.path
```
