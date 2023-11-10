---
Ability1: Vital Spirit
Ability2: ''
BookSprite: SRD-vigoroth-BookSprite.png
BoxSprite: SRD-vigoroth-BoxSprite.png
DexCategory: Wild Monkey Pokemon
DexDescription: "They are always agitated, anxious, excited or upset, rampaging over\
  \ anything. They can\u2019t be still and they can\u2019t sleep. They get angry if\
  \ they get bored and violent if there is no activity for them."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Slakoth]]'
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Slaking]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: ''
HomeSprite: SRD-vigoroth-HomeSprite.png
Image: vigoroth.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Reversal|Reversal]]'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Uproar|Uproar]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Chip Away|Chip Away]]'
- - Ace
  - '[[SRD-Focus Punch|Focus Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Crush Claw|Crush Claw]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
Number: 288
ShuffleToken: SRD-vigoroth-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 46.5
  Pounds: 102.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vigoroth-BookSprite.png|wsmall]]
> ![[SRD-vigoroth-HomeSprite.png]]
> ![[SRD-vigoroth-BoxSprite.png|htiny]]
> ![[SRD-vigoroth-ShuffleToken.png|wsmall]]


*Wild Monkey Pokemon*
*They are always agitated, anxious, excited or upset, rampaging over anything. They can’t be still and they can’t sleep. They get angry if they get bored and violent if there is no activity for them.*

**DexID**:: 0288
**Name**:: Vigoroth
**Type**:: Normal
**Abilities**:: [[SRD-Vital Spirit|Vital Spirit]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'6" / 1.4m
**Weight**: 102.5lbs / 46.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Slakoth]] | Level  | Slow    |
| To        | [[SRD-Slaking]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Vigoroth.md"
flatten moves as T
where file.path = this.file.path
```
