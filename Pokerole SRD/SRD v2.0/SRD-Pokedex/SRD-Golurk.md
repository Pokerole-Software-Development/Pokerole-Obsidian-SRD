---
Ability1: Iron Fist
Ability2: Klutz
BookSprite: SRD-golurk-BookSprite.png
BoxSprite: SRD-golurk-BoxSprite.png
DexCategory: Automaton Pokemon
DexDescription: It is said that Golurk were ordered to protect people and Pokemon
  by the ancient people who created them. There are records of only one still alive
  found on the ruin, the rest are just statues now.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Golett]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 9.2
  Meters: 2.8
HiddenAbility: No Guard
HomeSprite: SRD-golurk-HomeSprite.png
Image: golurk.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Shadow Punch|Shadow Punch]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Mega Punch|Mega Punch]]'
- - Amateur
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Amateur
  - '[[SRD-Magnitude|Magnitude]]'
- - Amateur
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - Amateur
  - '[[SRD-Night Shade|Night Shade]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Ace
  - '[[SRD-High Horsepower|High Horsepower]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Focus Punch|Focus Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Block|Block]]'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Number: 623
ShuffleToken: SRD-golurk-ShuffleToken.png
Type1: Ground
Type2: Ghost
Weight:
  Kilograms: 330.0
  Pounds: 727.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-golurk-BookSprite.png|wsmall]]
> ![[SRD-golurk-HomeSprite.png]]
> ![[SRD-golurk-BoxSprite.png|htiny]]
> ![[SRD-golurk-ShuffleToken.png|wsmall]]


*Automaton Pokemon*
*It is said that Golurk were ordered to protect people and Pokemon by the ancient people who created them. There are records of only one still alive found on the ruin, the rest are just statues now.*

**DexID**:: 0623
**Name**:: Golurk
**Type**:: Ground / Ghost
**Abilities**:: [[SRD-Iron Fist|Iron Fist]] / [[SRD-Klutz|Klutz]] ([[SRD-No Guard|No Guard]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 9'2" / 2.8m
**Weight**: 727.5lbs / 330.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Golett]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Golurk.md"
flatten moves as T
where file.path = this.file.path
```
