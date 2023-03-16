---
Ability1: Iron Fist
Ability2: Klutz
BookSprite: SRD-golett-BookSprite.png
BoxSprite: SRD-golett-BoxSprite.png
DexCategory: Automaton Pokemon
DexDescription: Very few have been seen in old ruins. These Pokemon are thought to
  have been created by the science of an ancient and mysterious civilization. The
  energy inside of it comes from an unknown source.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Golurk]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: No Guard
HomeSprite: SRD-golett-HomeSprite.png
Image: golett.png
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
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Curse|Curse]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Focus Punch|Focus Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
Number: 622
ShuffleToken: SRD-golett-ShuffleToken.png
Type1: Ground
Type2: Ghost
Weight:
  Kilograms: 92.0
  Pounds: 202.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-golett-BookSprite.png|wsmall]]
> ![[SRD-golett-HomeSprite.png]]
> ![[SRD-golett-BoxSprite.png|htiny]]
> ![[SRD-golett-ShuffleToken.png|wsmall]]


*Automaton Pokemon*
*Very few have been seen in old ruins. These Pokemon are thought to have been created by the science of an ancient and mysterious civilization. The energy inside of it comes from an unknown source.*

**DexID**:: 0622
**Name**:: Golett
**Type**:: Ground / Ghost
**Abilities**:: [[SRD-Iron Fist|Iron Fist]] / [[SRD-Klutz|Klutz]] ([[SRD-No Guard|No Guard]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 202.8lbs / 92.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Golurk]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Golett.md"
flatten moves as T
where file.path = this.file.path
```
