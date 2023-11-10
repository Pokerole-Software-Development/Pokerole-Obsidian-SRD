---
Ability1: Rock Head
Ability2: Sturdy
BookSprite: SRD-graveler-BookSprite.png
BoxSprite: SRD-graveler-BoxSprite.png
DexCategory: Rock Pokemon
DexDescription: It walks slowly, but it can get a nice speed by rolling downhill.
  It is good at climbing. Groups of them have been seen clinging from rock formations
  and cliffs to eat the tasty rocks covered in moss.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Geodude]]'
  Speed: Medium
- Evolves: To
  Kind: Trade
  Pokemon: '[[SRD-Golem]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Sand Veil
HomeSprite: SRD-graveler-HomeSprite.png
Image: graveler.png
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
Number: 75
ShuffleToken: SRD-graveler-ShuffleToken.png
Type1: Rock
Type2: Ground
Weight:
  Kilograms: 105.0
  Pounds: 231.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-graveler-BookSprite.png|wsmall]]
> ![[SRD-graveler-HomeSprite.png]]
> ![[SRD-graveler-BoxSprite.png|htiny]]
> ![[SRD-graveler-ShuffleToken.png|wsmall]]


*Rock Pokemon*
*It walks slowly, but it can get a nice speed by rolling downhill. It is good at climbing. Groups of them have been seen clinging from rock formations and cliffs to eat the tasty rocks covered in moss.*

**DexID**:: 0075
**Name**:: Graveler
**Type**:: Rock / Ground
**Abilities**:: [[SRD-Rock Head|Rock Head]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 231.5lbs / 105.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Geodude]] | Level  | Medium  |
| To        | [[SRD-Golem]]   | Trade  |         |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Graveler.md"
flatten moves as T
where file.path = this.file.path
```
