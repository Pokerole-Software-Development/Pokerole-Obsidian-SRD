---
Ability1: Overcoat
Ability2: Magic Guard
BookSprite: SRD-duosion-BookSprite.png
BoxSprite: SRD-duosion-BoxSprite.png
DexCategory: Mitosis Pokemon
DexDescription: "It developed two brains when it evolved, due to this it has a split\
  \ personality. At times it may suddenly try to take two different actions at once.\
  \ When the two brains finally synchronize it shows it\u2019s max power."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Solosis]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Reuniclus]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Regenerator
HomeSprite: SRD-duosion-HomeSprite.png
Image: duosion.png
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
Number: 578
ShuffleToken: SRD-duosion-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 8.0
  Pounds: 17.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-duosion-BookSprite.png|wsmall]]
> ![[SRD-duosion-HomeSprite.png]]
> ![[SRD-duosion-BoxSprite.png|htiny]]
> ![[SRD-duosion-ShuffleToken.png|wsmall]]


*Mitosis Pokemon*
*It developed two brains when it evolved, due to this it has a split personality. At times it may suddenly try to take two different actions at once. When the two brains finally synchronize it shows it’s max power.*

**DexID**:: 0578
**Name**:: Duosion
**Type**:: Psychic
**Abilities**:: [[SRD-Overcoat|Overcoat]] / [[SRD-Magic Guard|Magic Guard]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 17.6lbs / 8.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Solosis]]   | Level  | Medium  |
| To        | [[SRD-Reuniclus]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Duosion.md"
flatten moves as T
where file.path = this.file.path
```
