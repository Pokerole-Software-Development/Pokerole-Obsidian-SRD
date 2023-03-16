---
Ability1: Sand Veil
Ability2: ''
BookSprite: SRD-sandslash-BookSprite.png
BoxSprite: SRD-sandslash-BoxSprite.png
DexCategory: Mouse Pokemon
DexDescription: "It\u2019s less shy than its first stage. It curls up in a ball to\
  \ protect itself from enemy attacks. Surprisingly, it is a good climber that uses\
  \ its sharp claws for grip and drilling tunnels underground."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Sandshrew]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Sand Rush
HomeSprite: SRD-sandslash-HomeSprite.png
Image: sandslash.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Magnitude|Magnitude]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Crush Claw|Crush Claw]]'
- - Amateur
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - Ace
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
Number: 28
ShuffleToken: SRD-sandslash-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 29.5
  Pounds: 65.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sandslash-BookSprite.png|wsmall]]
> ![[SRD-sandslash-HomeSprite.png]]
> ![[SRD-sandslash-BoxSprite.png|htiny]]
> ![[SRD-sandslash-ShuffleToken.png|wsmall]]


*Mouse Pokemon*
*It’s less shy than its first stage. It curls up in a ball to protect itself from enemy attacks. Surprisingly, it is a good climber that uses its sharp claws for grip and drilling tunnels underground.*

**DexID**:: 0028
**Name**:: Sandslash
**Type**:: Ground
**Abilities**:: [[SRD-Sand Veil|Sand Veil]] ([[SRD-Sand Rush|Sand Rush]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 65.0lbs / 29.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Sandshrew]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Sandslash.md"
flatten moves as T
where file.path = this.file.path
```
