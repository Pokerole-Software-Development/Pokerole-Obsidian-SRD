---
Ability1: Overcoat
Ability2: Magic Guard
BookSprite: SRD-solosis-BookSprite.png
BoxSprite: SRD-solosis-BoxSprite.png
DexCategory: Cell Pokemon
DexDescription: Because their bodies are enveloped in a special liquid, they can survive
  in any environment. They drive away attackers by unleashing their psychic power.
  They communicate with their minds.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Duosion]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Regenerator
HomeSprite: SRD-solosis-HomeSprite.png
Image: solosis.png
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
Number: 577
ShuffleToken: SRD-solosis-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 1.0
  Pounds: 2.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-solosis-BookSprite.png|wsmall]]
> ![[SRD-solosis-HomeSprite.png]]
> ![[SRD-solosis-BoxSprite.png|htiny]]
> ![[SRD-solosis-ShuffleToken.png|wsmall]]


*Cell Pokemon*
*Because their bodies are enveloped in a special liquid, they can survive in any environment. They drive away attackers by unleashing their psychic power. They communicate with their minds.*

**DexID**:: 0577
**Name**:: Solosis
**Type**:: Psychic
**Abilities**:: [[SRD-Overcoat|Overcoat]] / [[SRD-Magic Guard|Magic Guard]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 2.2lbs / 1.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Duosion]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Solosis.md"
flatten moves as T
where file.path = this.file.path
```
