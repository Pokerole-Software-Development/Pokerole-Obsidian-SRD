---
Ability1: Oblivious
Ability2: Simple
BookSprite: SRD-numel-BookSprite.png
BoxSprite: SRD-numel-BoxSprite.png
DexCategory: Numb Pokemon
DexDescription: "An incredibly dim-witted Pokemon. They don\u2019t notice being hit.\
  \ If they get hungry they faint. Numel's body is a cauldron of boiling magma. In\
  \ rainy days, the magma cools and its speed is lowered."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Camerupt]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Own Tempo
HomeSprite: SRD-numel-HomeSprite.png
Image: numel.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Magnitude|Magnitude]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Amateur
  - '[[SRD-Earth Power|Earth Power]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Pro
  - '[[SRD-Growth|Growth]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 322
ShuffleToken: SRD-numel-ShuffleToken.png
Type1: Fire
Type2: Ground
Weight:
  Kilograms: 24.0
  Pounds: 52.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-numel-BookSprite.png|wsmall]]
> ![[SRD-numel-HomeSprite.png]]
> ![[SRD-numel-BoxSprite.png|htiny]]
> ![[SRD-numel-ShuffleToken.png|wsmall]]


*Numb Pokemon*
*An incredibly dim-witted Pokemon. They don’t notice being hit. If they get hungry they faint. Numel's body is a cauldron of boiling magma. In rainy days, the magma cools and its speed is lowered.*

**DexID**:: 0322
**Name**:: Numel
**Type**:: Fire / Ground
**Abilities**:: [[SRD-Oblivious|Oblivious]] / [[SRD-Simple|Simple]] ([[SRD-Own Tempo|Own Tempo]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 52.9lbs / 24.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Camerupt]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Numel.md"
flatten moves as T
where file.path = this.file.path
```
