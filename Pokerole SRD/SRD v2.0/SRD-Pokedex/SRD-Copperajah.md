---
Ability1: Sheer Force
Ability2: ''
BookSprite: SRD-copperajah-BookSprite.png
BoxSprite: SRD-copperajah-BoxSprite.png
DexCategory: Copperderm Pokemon
DexDescription: They originally came from another region long ago, worked together
  with humans helping them pave new roads and building cities. They are usually calm
  and love spending time with their families.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Cufant]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 9.8
  Meters: 3.0
HiddenAbility: Heavy Metal
HomeSprite: SRD-copperajah-HomeSprite.png
Image: copperajah.png
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
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fissure|Fissure]]'
- - Pro
  - '[[SRD-Power Whip|Power Whip]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 879
ShuffleToken: SRD-copperajah-ShuffleToken.png
Type1: Steel
Type2: ''
Weight:
  Kilograms: 650.0
  Pounds: 1433.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-copperajah-BookSprite.png|wsmall]]
> ![[SRD-copperajah-HomeSprite.png]]
> ![[SRD-copperajah-BoxSprite.png|htiny]]
> ![[SRD-copperajah-ShuffleToken.png|wsmall]]


*Copperderm Pokemon*
*They originally came from another region long ago, worked together with humans helping them pave new roads and building cities. They are usually calm and love spending time with their families.*

**DexID**:: 0879
**Name**:: Copperajah
**Type**:: Steel
**Abilities**:: [[SRD-Sheer Force|Sheer Force]] ([[SRD-Heavy Metal|Heavy Metal]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 9'8" / 3.0m
**Weight**: 1433.0lbs / 650.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Cufant]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Copperajah.md"
flatten moves as T
where file.path = this.file.path
```
