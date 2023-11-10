---
Ability1: Sheer Force
Ability2: ''
BookSprite: SRD-cufant-BookSprite.png
BoxSprite: SRD-cufant-BoxSprite.png
DexCategory: Copperderm Pokemon
DexDescription: If a job requires serious strength, this Pokemon will excel at it.
  Its copper body tarnishes in the rain, turning a vibrant green color. Its trunk
  is specially designed to dig the ground, in the wild they uproot trees to eat.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Copperajah]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Heavy Metal
HomeSprite: SRD-cufant-HomeSprite.png
Image: cufant.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Strength|Strength]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - Amateur
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-High Horsepower|High Horsepower]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Pro
  - '[[SRD-Fissure|Fissure]]'
Number: 878
ShuffleToken: SRD-cufant-ShuffleToken.png
Type1: Steel
Type2: ''
Weight:
  Kilograms: 100.0
  Pounds: 220.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cufant-BookSprite.png|wsmall]]
> ![[SRD-cufant-HomeSprite.png]]
> ![[SRD-cufant-BoxSprite.png|htiny]]
> ![[SRD-cufant-ShuffleToken.png|wsmall]]


*Copperderm Pokemon*
*If a job requires serious strength, this Pokemon will excel at it. Its copper body tarnishes in the rain, turning a vibrant green color. Its trunk is specially designed to dig the ground, in the wild they uproot trees to eat.*

**DexID**:: 0878
**Name**:: Cufant
**Type**:: Steel
**Abilities**:: [[SRD-Sheer Force|Sheer Force]] ([[SRD-Heavy Metal|Heavy Metal]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 220.5lbs / 100.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Copperajah]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cufant.md"
flatten moves as T
where file.path = this.file.path
```
