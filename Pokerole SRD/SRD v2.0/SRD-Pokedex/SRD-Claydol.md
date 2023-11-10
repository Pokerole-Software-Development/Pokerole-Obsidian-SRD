---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-claydol-BookSprite.png
BoxSprite: SRD-claydol-BoxSprite.png
DexCategory: Clay Doll Pokemon
DexDescription: It is made entirely of clay. The first one was discovered in ruins
  from 20,000 years ago. A strange light is said to be the source of its life and
  psychic abilities. Its eight eyes are always alert and always watching.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Baltoy]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: ''
HomeSprite: SRD-claydol-HomeSprite.png
Image: claydol.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Beginner
  - '[[SRD-Teleport|Teleport]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Heal Block|Heal Block]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Power Trick|Power Trick]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Amateur
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Amateur
  - '[[SRD-Guard Split|Guard Split]]'
- - Amateur
  - '[[SRD-Power Split|Power Split]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Earth Power|Earth Power]]'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Imprison|Imprison]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
Number: 344
ShuffleToken: SRD-claydol-ShuffleToken.png
Type1: Ground
Type2: Psychic
Weight:
  Kilograms: 108.0
  Pounds: 238.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-claydol-BookSprite.png|wsmall]]
> ![[SRD-claydol-HomeSprite.png]]
> ![[SRD-claydol-BoxSprite.png|htiny]]
> ![[SRD-claydol-ShuffleToken.png|wsmall]]


*Clay Doll Pokemon*
*It is made entirely of clay. The first one was discovered in ruins from 20,000 years ago. A strange light is said to be the source of its life and psychic abilities. Its eight eyes are always alert and always watching.*

**DexID**:: 0344
**Name**:: Claydol
**Type**:: Ground / Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 238.1lbs / 108.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Baltoy]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Claydol.md"
flatten moves as T
where file.path = this.file.path
```
