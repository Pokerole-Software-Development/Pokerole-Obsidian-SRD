---
Ability1: Swarm
Ability2: Insomnia
BookSprite: SRD-spinarak-BookSprite.png
BoxSprite: SRD-spinarak-BoxSprite.png
DexCategory: String Spit Pokemon
DexDescription: It sets a trap by spinning a web of thin but strong silk. Then it
  waits for the prey to arrive. It recognizes what kind of prey has fallen on its
  web by the vibrations received by each one of its eight legs.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Ariados]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Sniper
HomeSprite: SRD-spinarak-HomeSprite.png
Image: spinarak.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Scary Face|Scary Face]]'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Infestation|Infestation]]'
- - Beginner
  - '[[SRD-Constrict|Constrict]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Leech Life|Leech Life]]'
- - Amateur
  - '[[SRD-Night Shade|Night Shade]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Spider Web|Spider Web]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Cross Poison|Cross Poison]]'
- - Ace
  - '[[SRD-Sticky Web|Sticky Web]]'
- - Ace
  - '[[SRD-Toxic Thread|Toxic Thread]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
Number: 167
ShuffleToken: SRD-spinarak-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 8.5
  Pounds: 18.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-spinarak-BookSprite.png|wsmall]]
> ![[SRD-spinarak-HomeSprite.png]]
> ![[SRD-spinarak-BoxSprite.png|htiny]]
> ![[SRD-spinarak-ShuffleToken.png|wsmall]]


*String Spit Pokemon*
*It sets a trap by spinning a web of thin but strong silk. Then it waits for the prey to arrive. It recognizes what kind of prey has fallen on its web by the vibrations received by each one of its eight legs.*

**DexID**:: 0167
**Name**:: Spinarak
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Insomnia|Insomnia]] ([[SRD-Sniper|Sniper]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 18.7lbs / 8.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Ariados]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Spinarak.md"
flatten moves as T
where file.path = this.file.path
```
