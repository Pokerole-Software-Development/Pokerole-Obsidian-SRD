---
Ability1: Own Tempo
Ability2: Stamina
BookSprite: SRD-mudbray-BookSprite.png
BoxSprite: SRD-mudbray-BoxSprite.png
DexCategory: Donkey Pokemon
DexDescription: They are very strong, the mud on their hooves serves them as grip
  to pull themselves forward. They enjoy prancing in muddy places and will become
  stubborn and disobedient if denied that pleasure.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Mudsdale]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Inner Focus
HomeSprite: SRD-mudbray-HomeSprite.png
Image: mudbray.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rototiller|Rototiller]]'
- - Beginner
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Beginner
  - '[[SRD-Double Kick|Double Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-High Horsepower|High Horsepower]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Mega Kick|Mega Kick]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Magnitude|Magnitude]]'
- - Pro
  - '[[SRD-Strength|Strength]]'
- - Pro
  - '[[SRD-Mud Bomb|Mud Bomb]]'
Number: 749
ShuffleToken: SRD-mudbray-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 110.0
  Pounds: 242.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mudbray-BookSprite.png|wsmall]]
> ![[SRD-mudbray-HomeSprite.png]]
> ![[SRD-mudbray-BoxSprite.png|htiny]]
> ![[SRD-mudbray-ShuffleToken.png|wsmall]]


*Donkey Pokemon*
*They are very strong, the mud on their hooves serves them as grip to pull themselves forward. They enjoy prancing in muddy places and will become stubborn and disobedient if denied that pleasure.*

**DexID**:: 0749
**Name**:: Mudbray
**Type**:: Ground
**Abilities**:: [[SRD-Own Tempo|Own Tempo]] / [[SRD-Stamina|Stamina]] ([[SRD-Inner Focus|Inner Focus]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 242.5lbs / 110.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Mudsdale]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Mudbray.md"
flatten moves as T
where file.path = this.file.path
```
