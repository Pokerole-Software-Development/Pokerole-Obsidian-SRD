---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-typhlosion-BookSprite.png
BoxSprite: SRD-typhlosion-BoxSprite.png
DexCategory: Volcano Pokemon
DexDescription: Very rare to see in the wild. It hides behind a shimmering heat haze
  created using its fire. Typhlosion can create eruptions and explosive blasts that
  can burn everything to the ground.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Quilava]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Flash Fire
HomeSprite: SRD-typhlosion-HomeSprite.png
Image: typhlosion.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Eruption|Eruption]]'
- - Ace
  - '[[SRD-Burn Up|Burn Up]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Blast Burn|Blast Burn]]'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
Number: 157
ShuffleToken: SRD-typhlosion-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 79.5
  Pounds: 175.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-typhlosion-BookSprite.png|wsmall]]
> ![[SRD-typhlosion-HomeSprite.png]]
> ![[SRD-typhlosion-BoxSprite.png|htiny]]
> ![[SRD-typhlosion-ShuffleToken.png|wsmall]]


*Volcano Pokemon*
*Very rare to see in the wild. It hides behind a shimmering heat haze created using its fire. Typhlosion can create eruptions and explosive blasts that can burn everything to the ground.*

**DexID**:: 0157
**Name**:: Typhlosion
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Flash Fire|Flash Fire]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 175.3lbs / 79.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Quilava]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Typhlosion.md"
flatten moves as T
where file.path = this.file.path
```
