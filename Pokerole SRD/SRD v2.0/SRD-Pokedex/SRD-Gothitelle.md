---
Ability1: Frisk
Ability2: Competitive
BookSprite: SRD-gothitelle-BookSprite.png
BoxSprite: SRD-gothitelle-BoxSprite.png
DexCategory: Astral Body Pokemon
DexDescription: They can predict the future from the placement and movement of the
  stars. They get restless if someone they know will be in danger. They are emphatic
  creatures that can understand human emotion.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Gothorita]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Shadow Tag
HomeSprite: SRD-gothitelle-HomeSprite.png
Image: gothitelle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tickle|Tickle]]'
- - Beginner
  - '[[SRD-Play Nice|Play Nice]]'
- - Beginner
  - '[[SRD-Fake Tears|Fake Tears]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Psyshock|Psyshock]]'
- - Amateur
  - '[[SRD-Flatter|Flatter]]'
- - Amateur
  - '[[SRD-Future Sight|Future Sight]]'
- - Amateur
  - '[[SRD-Heal Block|Heal Block]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Ace
  - '[[SRD-Charm|Charm]]'
- - Ace
  - '[[SRD-Magic Room|Magic Room]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Dark Pulse|Dark Pulse]]'
Number: 576
ShuffleToken: SRD-gothitelle-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 44.0
  Pounds: 97.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gothitelle-BookSprite.png|wsmall]]
> ![[SRD-gothitelle-HomeSprite.png]]
> ![[SRD-gothitelle-BoxSprite.png|htiny]]
> ![[SRD-gothitelle-ShuffleToken.png|wsmall]]


*Astral Body Pokemon*
*They can predict the future from the placement and movement of the stars. They get restless if someone they know will be in danger. They are emphatic creatures that can understand human emotion.*

**DexID**:: 0576
**Name**:: Gothitelle
**Type**:: Psychic
**Abilities**:: [[SRD-Frisk|Frisk]] / [[SRD-Competitive|Competitive]] ([[SRD-Shadow Tag|Shadow Tag]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 97.0lbs / 44.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Gothorita]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gothitelle.md"
flatten moves as T
where file.path = this.file.path
```
