---
Ability1: Swift Swim
Ability2: Shell Armor
BookSprite: SRD-omastar-BookSprite.png
BoxSprite: SRD-omastar-BoxSprite.png
DexCategory: Spiral Pokemon
DexDescription: An Omastar used its tentacles to ensnare and capture its prey. It
  is believed to have become extinct because the shell grew too large, making it slow
  and ponderous. It is not found in the wild anymore.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Omanyte]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Weak Armor
HomeSprite: SRD-omastar-HomeSprite.png
Image: omastar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Leer|Leer]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Spike Cannon|Spike Cannon]]'
- - Amateur
  - '[[SRD-Tickle|Tickle]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
Number: 139
ShuffleToken: SRD-omastar-ShuffleToken.png
Type1: Rock
Type2: Water
Weight:
  Kilograms: 35.0
  Pounds: 77.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-omastar-BookSprite.png|wsmall]]
> ![[SRD-omastar-HomeSprite.png]]
> ![[SRD-omastar-BoxSprite.png|htiny]]
> ![[SRD-omastar-ShuffleToken.png|wsmall]]


*Spiral Pokemon*
*An Omastar used its tentacles to ensnare and capture its prey. It is believed to have become extinct because the shell grew too large, making it slow and ponderous. It is not found in the wild anymore.*

**DexID**:: 0139
**Name**:: Omastar
**Type**:: Rock / Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Shell Armor|Shell Armor]] ([[SRD-Weak Armor|Weak Armor]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 77.2lbs / 35.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Omanyte]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Omastar.md"
flatten moves as T
where file.path = this.file.path
```
