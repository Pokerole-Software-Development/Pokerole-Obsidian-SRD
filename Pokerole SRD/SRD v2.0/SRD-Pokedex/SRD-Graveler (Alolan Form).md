---
Ability1: Magnet Pull
Ability2: Sturdy
BookSprite: SRD-graveler-alolan-form-BookSprite.png
BoxSprite: SRD-graveler-alolan-form-BoxSprite.png
DexCategory: Rock Pokemon
DexDescription: These Pokemon charge themselves by rolling around, it is dangerous
  if two of them collide, a loud noise and a flash of light will be seen and heard
  at great distance. They feed on golden dravite.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Geodude (Alolan Form)]]'
  Speed: Medium
- Evolves: To
  Kind: Trade
  Pokemon: '[[SRD-Golem (Alolan Form)]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Galvanize
HomeSprite: SRD-graveler-alolan-form-HomeSprite.png
Image: graveler-alolan-form.png
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
Number: 75
ShuffleToken: SRD-graveler-alolan-form-ShuffleToken.png
Type1: Rock
Type2: Electric
Weight:
  Kilograms: 110.0
  Pounds: 242.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-graveler-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-graveler-alolan-form-HomeSprite.png]]
> ![[SRD-graveler-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-graveler-alolan-form-ShuffleToken.png|wsmall]]


*Rock Pokemon*
*These Pokemon charge themselves by rolling around, it is dangerous if two of them collide, a loud noise and a flash of light will be seen and heard at great distance. They feed on golden dravite.*

**DexID**:: 0075A
**Name**:: Graveler (Alolan Form)
**Type**:: Rock / Electric
**Abilities**:: [[SRD-Magnet Pull|Magnet Pull]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Galvanize|Galvanize]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 242.5lbs / 110.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                       | Kind   | Speed   |
|:----------|:------------------------------|:-------|:--------|
| From      | [[SRD-Geodude (Alolan Form)]] | Level  | Medium  |
| To        | [[SRD-Golem (Alolan Form)]]   | Trade  |         |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Graveler (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
