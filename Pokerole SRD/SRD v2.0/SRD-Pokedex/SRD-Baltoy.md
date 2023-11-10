---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-baltoy-BookSprite.png
BoxSprite: SRD-baltoy-BoxSprite.png
DexCategory: Clay Doll Pokemon
DexDescription: They spin on their center to move around. When a group of them gathers
  they create a horrible, headache inducing noise at unison. Old paintings describe
  them living with people in ancient times.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Claydol]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: ''
HomeSprite: SRD-baltoy-HomeSprite.png
Image: baltoy.png
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
  - '[[SRD-Guard Split|Guard Split]]'
- - Amateur
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Amateur
  - '[[SRD-Power Split|Power Split]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Ace
  - '[[SRD-Earth Power|Earth Power]]'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Number: 343
ShuffleToken: SRD-baltoy-ShuffleToken.png
Type1: Ground
Type2: Psychic
Weight:
  Kilograms: 21.5
  Pounds: 47.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-baltoy-BookSprite.png|wsmall]]
> ![[SRD-baltoy-HomeSprite.png]]
> ![[SRD-baltoy-BoxSprite.png|htiny]]
> ![[SRD-baltoy-ShuffleToken.png|wsmall]]


*Clay Doll Pokemon*
*They spin on their center to move around. When a group of them gathers they create a horrible, headache inducing noise at unison. Old paintings describe them living with people in ancient times.*

**DexID**:: 0343
**Name**:: Baltoy
**Type**:: Ground / Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'6" / 0.5m
**Weight**: 47.4lbs / 21.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Claydol]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Baltoy.md"
flatten moves as T
where file.path = this.file.path
```
