---
Ability1: Rock Head
Ability2: Sturdy
BookSprite: SRD-geodude-BookSprite.png
BoxSprite: SRD-geodude-BoxSprite.png
DexCategory: Rock Pokemon
DexDescription: Lives in mountains and caves. It looks indistinguishable from other
  rocks around. Because of this, many trainers step on them and are attacked. It rolls
  to move around and eats whatever it finds on the floor.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Graveler]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Sand Veil
HomeSprite: SRD-geodude-HomeSprite.png
Image: geodude.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Beginner
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Magnitude|Magnitude]]'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rock Climb|Rock Climb]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
Number: 74
ShuffleToken: SRD-geodude-ShuffleToken.png
Type1: Rock
Type2: Ground
Weight:
  Kilograms: 20.0
  Pounds: 44.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-geodude-BookSprite.png|wsmall]]
> ![[SRD-geodude-HomeSprite.png]]
> ![[SRD-geodude-BoxSprite.png|htiny]]
> ![[SRD-geodude-ShuffleToken.png|wsmall]]


*Rock Pokemon*
*Lives in mountains and caves. It looks indistinguishable from other rocks around. Because of this, many trainers step on them and are attacked. It rolls to move around and eats whatever it finds on the floor.*

**DexID**:: 0074
**Name**:: Geodude
**Type**:: Rock / Ground
**Abilities**:: [[SRD-Rock Head|Rock Head]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 44.1lbs / 20.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Graveler]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Geodude.md"
flatten moves as T
where file.path = this.file.path
```
