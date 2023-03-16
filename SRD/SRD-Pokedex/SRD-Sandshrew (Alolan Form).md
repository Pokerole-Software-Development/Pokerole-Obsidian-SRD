---
Ability1: Snow Cloak
Ability2: ''
BookSprite: SRD-sandshrew-alolan-form-BookSprite.png
BoxSprite: SRD-sandshrew-alolan-form-BoxSprite.png
DexCategory: Mouse Pokemon
DexDescription: Sandshrew who became trapped in the merciless cold weather of Alola
  had to change their types to survive. They now depend on snow to roll around, without
  it they are unable to curl up into a ball.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Sandslash (Alolan Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Slush Rush
HomeSprite: SRD-sandshrew-alolan-form-HomeSprite.png
Image: sandshrew-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - Beginner
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Ball|Ice Ball]]'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Chip Away|Chip Away]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
- - Pro
  - '[[SRD-Aerial Ace|Aerial Ace]]'
Number: 27
ShuffleToken: SRD-sandshrew-alolan-form-ShuffleToken.png
Type1: Ice
Type2: Steel
Weight:
  Kilograms: 40.0
  Pounds: 88.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sandshrew-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-sandshrew-alolan-form-HomeSprite.png]]
> ![[SRD-sandshrew-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-sandshrew-alolan-form-ShuffleToken.png|wsmall]]


*Mouse Pokemon*
*Sandshrew who became trapped in the merciless cold weather of Alola had to change their types to survive. They now depend on snow to roll around, without it they are unable to curl up into a ball.*

**DexID**:: 0027A
**Name**:: Sandshrew (Alolan Form)
**Type**:: Ice / Steel
**Abilities**:: [[SRD-Snow Cloak|Snow Cloak]] ([[SRD-Slush Rush|Slush Rush]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::2)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'3" / 0.7m
**Weight**: 88.2lbs / 40.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                         | Kind   | Speed   |
|:----------|:--------------------------------|:-------|:--------|
| To        | [[SRD-Sandslash (Alolan Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Sandshrew (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
