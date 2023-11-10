---
Ability1: Soundproof
Ability2: Static
BookSprite: SRD-electrode-BookSprite.png
BoxSprite: SRD-electrode-BoxSprite.png
DexCategory: Ball Pokemon
DexDescription: It is known for causing blackouts in the cities. After evolving it
  explodes as a form to release excess electricity or simply to amuse itself. Trainers
  need to be careful around an Electrode.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Voltorb]]'
  Speed: Slow
GenderType: N
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Aftermath
HomeSprite: SRD-electrode-HomeSprite.png
Image: electrode.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Charge|Charge]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Eerie Impulse|Eerie Impulse]]'
- - Beginner
  - '[[SRD-Sonic Boom|Sonic Boom]]'
- - Beginner
  - '[[SRD-Spark|Spark]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Magnetic Flux|Magnetic Flux]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Charge Beam|Charge Beam]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Discharge|Discharge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Ace
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - Ace
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 101
ShuffleToken: SRD-electrode-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 66.6
  Pounds: 146.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-electrode-BookSprite.png|wsmall]]
> ![[SRD-electrode-HomeSprite.png]]
> ![[SRD-electrode-BoxSprite.png|htiny]]
> ![[SRD-electrode-ShuffleToken.png|wsmall]]


*Ball Pokemon*
*It is known for causing blackouts in the cities. After evolving it explodes as a form to release excess electricity or simply to amuse itself. Trainers need to be careful around an Electrode.*

**DexID**:: 0101
**Name**:: Electrode
**Type**:: Electric
**Abilities**:: [[SRD-Soundproof|Soundproof]] / [[SRD-Static|Static]] ([[SRD-Aftermath|Aftermath]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::8) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 146.8lbs / 66.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Voltorb]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Electrode.md"
flatten moves as T
where file.path = this.file.path
```
