---
Ability1: Magnet Pull
Ability2: Sturdy
BookSprite: SRD-geodude-alolan-form-BookSprite.png
BoxSprite: SRD-geodude-alolan-form-BoxSprite.png
DexCategory: Rock Pokemon
DexDescription: "The magnetic fields on Alola\u2019s Blush Mountain made Geodude develop\
  \ Electric chargers on its body. They tend to disguise themselves as regular rocks,\
  \ caution is advised as they shock you if you step on them."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Graveler (Alolan Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Galvanize
HomeSprite: SRD-geodude-alolan-form-HomeSprite.png
Image: geodude-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Charge|Charge]]'
- - Beginner
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
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
  - '[[SRD-Screech|Screech]]'
Number: 74
ShuffleToken: SRD-geodude-alolan-form-ShuffleToken.png
Type1: Rock
Type2: Electric
Weight:
  Kilograms: 20.3
  Pounds: 44.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-geodude-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-geodude-alolan-form-HomeSprite.png]]
> ![[SRD-geodude-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-geodude-alolan-form-ShuffleToken.png|wsmall]]


*Rock Pokemon*
*The magnetic fields on Alola’s Blush Mountain made Geodude develop Electric chargers on its body. They tend to disguise themselves as regular rocks, caution is advised as they shock you if you step on them.*

**DexID**:: 0074A
**Name**:: Geodude (Alolan Form)
**Type**:: Rock / Electric
**Abilities**:: [[SRD-Magnet Pull|Magnet Pull]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Galvanize|Galvanize]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 44.8lbs / 20.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                        | Kind   | Speed   |
|:----------|:-------------------------------|:-------|:--------|
| To        | [[SRD-Graveler (Alolan Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Geodude (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
