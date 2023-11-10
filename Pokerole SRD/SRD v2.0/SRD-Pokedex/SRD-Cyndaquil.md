---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-cyndaquil-BookSprite.png
BoxSprite: SRD-cyndaquil-BoxSprite.png
DexCategory: Fire Mouse Pokemon
DexDescription: "A shy and elusive Pokemon. The flames from its back protect it. They\u2019\
  ll burn vigorously if Cyndaquil is angry otherwise they\u2019ll remain unlit. It\
  \ lives in hot dens inside of mountains and volcanoes."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Quilava]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Flash Fire
HomeSprite: SRD-cyndaquil-HomeSprite.png
Image: cyndaquil.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
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
  - '[[SRD-Howl|Howl]]'
- - Pro
  - '[[SRD-Double Kick|Double Kick]]'
- - Pro
  - '[[SRD-Fire Pledge|Fire Pledge]]'
Number: 155
ShuffleToken: SRD-cyndaquil-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 7.9
  Pounds: 17.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cyndaquil-BookSprite.png|wsmall]]
> ![[SRD-cyndaquil-HomeSprite.png]]
> ![[SRD-cyndaquil-BoxSprite.png|htiny]]
> ![[SRD-cyndaquil-ShuffleToken.png|wsmall]]


*Fire Mouse Pokemon*
*A shy and elusive Pokemon. The flames from its back protect it. They’ll burn vigorously if Cyndaquil is angry otherwise they’ll remain unlit. It lives in hot dens inside of mountains and volcanoes.*

**DexID**:: 0155
**Name**:: Cyndaquil
**Type**:: Fire
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Flash Fire|Flash Fire]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 17.4lbs / 7.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Quilava]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cyndaquil.md"
flatten moves as T
where file.path = this.file.path
```
