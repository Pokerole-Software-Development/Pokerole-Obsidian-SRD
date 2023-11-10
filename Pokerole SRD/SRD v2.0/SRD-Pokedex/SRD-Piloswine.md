---
Ability1: Oblivious
Ability2: Snow Cloak
BookSprite: SRD-piloswine-BookSprite.png
BoxSprite: SRD-piloswine-BoxSprite.png
DexCategory: Swine Pokemon
DexDescription: "Their long hair obscure their sight, but they\u2019re sensitive to\
  \ sound and smells. Piloswine's rugged hooves prevent it from slipping on icy terrains.\
  \ Amazingly, their tusks are made of solid ice."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Swinub]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Mamoswine]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Thick Fat
HomeSprite: SRD-piloswine-HomeSprite.png
Image: piloswine.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Starter
  - '[[SRD-Mud Slap|Mud Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - Beginner
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Amnesia|Amnesia]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - Pro
  - '[[SRD-Body Slam|Body Slam]]'
- - Pro
  - '[[SRD-Avalanche|Avalanche]]'
Number: 221
ShuffleToken: SRD-piloswine-ShuffleToken.png
Type1: Ice
Type2: Ground
Weight:
  Kilograms: 55.8
  Pounds: 123.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-piloswine-BookSprite.png|wsmall]]
> ![[SRD-piloswine-HomeSprite.png]]
> ![[SRD-piloswine-BoxSprite.png|htiny]]
> ![[SRD-piloswine-ShuffleToken.png|wsmall]]


*Swine Pokemon*
*Their long hair obscure their sight, but they’re sensitive to sound and smells. Piloswine's rugged hooves prevent it from slipping on icy terrains. Amazingly, their tusks are made of solid ice.*

**DexID**:: 0221
**Name**:: Piloswine
**Type**:: Ice / Ground
**Abilities**:: [[SRD-Oblivious|Oblivious]] / [[SRD-Snow Cloak|Snow Cloak]] ([[SRD-Thick Fat|Thick Fat]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 123.0lbs / 55.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Swinub]]    | Level  | Medium  |
| To        | [[SRD-Mamoswine]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Piloswine.md"
flatten moves as T
where file.path = this.file.path
```
