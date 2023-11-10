---
Ability1: Stakeout
Ability2: Strong Jaw
BookSprite: SRD-gumshoos-BookSprite.png
BoxSprite: SRD-gumshoos-BoxSprite.png
DexCategory: Stakeout Pokemon
DexDescription: Alolan Ratatta became nocturnal to evade this Pokemon, as it is their
  main Predator. Gumshoos now go hungry for days before they find something suitable
  to eat, they compensate by sleeping a lot.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Yungoos]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Adaptability
HomeSprite: SRD-gumshoos-HomeSprite.png
Image: gumshoos.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Super Fang|Super Fang]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hyper Fang|Hyper Fang]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Revenge|Revenge]]'
- - Pro
  - '[[SRD-Sleep Talk|Sleep Talk]]'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
Number: 735
ShuffleToken: SRD-gumshoos-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 14.2
  Pounds: 31.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gumshoos-BookSprite.png|wsmall]]
> ![[SRD-gumshoos-HomeSprite.png]]
> ![[SRD-gumshoos-BoxSprite.png|htiny]]
> ![[SRD-gumshoos-ShuffleToken.png|wsmall]]


*Stakeout Pokemon*
*Alolan Ratatta became nocturnal to evade this Pokemon, as it is their main Predator. Gumshoos now go hungry for days before they find something suitable to eat, they compensate by sleeping a lot.*

**DexID**:: 0735
**Name**:: Gumshoos
**Type**:: Normal
**Abilities**:: [[SRD-Stakeout|Stakeout]] / [[SRD-Strong Jaw|Strong Jaw]] ([[SRD-Adaptability|Adaptability]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 31.3lbs / 14.2kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Yungoos]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gumshoos.md"
flatten moves as T
where file.path = this.file.path
```
