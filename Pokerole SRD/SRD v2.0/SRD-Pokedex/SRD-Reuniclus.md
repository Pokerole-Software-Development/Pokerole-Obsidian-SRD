---
Ability1: Overcoat
Ability2: Magic Guard
BookSprite: SRD-reuniclus-BookSprite.png
BoxSprite: SRD-reuniclus-BoxSprite.png
DexCategory: Multiplying Pokemon
DexDescription: These intelligent Pokemon fight by controlling their arms with psychic
  energy. They have been seen forming networks of many Reuniclus holding hands and
  unleashing an incredible psychic wave.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Duosion]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Regenerator
HomeSprite: SRD-reuniclus-HomeSprite.png
Image: reuniclus.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Psywave|Psywave]]'
- - Starter
  - '[[SRD-Reflect|Reflect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - Beginner
  - '[[SRD-Snatch|Snatch]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Psyshock|Psyshock]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - Amateur
  - '[[SRD-Pain Split|Pain Split]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Dizzy Punch|Dizzy Punch]]'
- - Ace
  - '[[SRD-Skill Swap|Skill Swap]]'
- - Ace
  - '[[SRD-Heal Block|Heal Block]]'
- - Ace
  - '[[SRD-Wonder Room|Wonder Room]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[SRD-Night Shade|Night Shade]]'
- - Pro
  - '[[SRD-Confuse Ray|Confuse Ray]]'
Number: 579
ShuffleToken: SRD-reuniclus-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 20.1
  Pounds: 44.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-reuniclus-BookSprite.png|wsmall]]
> ![[SRD-reuniclus-HomeSprite.png]]
> ![[SRD-reuniclus-BoxSprite.png|htiny]]
> ![[SRD-reuniclus-ShuffleToken.png|wsmall]]


*Multiplying Pokemon*
*These intelligent Pokemon fight by controlling their arms with psychic energy. They have been seen forming networks of many Reuniclus holding hands and unleashing an incredible psychic wave.*

**DexID**:: 0579
**Name**:: Reuniclus
**Type**:: Psychic
**Abilities**:: [[SRD-Overcoat|Overcoat]] / [[SRD-Magic Guard|Magic Guard]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 44.3lbs / 20.1kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Duosion]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Reuniclus.md"
flatten moves as T
where file.path = this.file.path
```
