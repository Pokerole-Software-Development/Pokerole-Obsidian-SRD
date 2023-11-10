---
Ability1: Snow Cloak
Ability2: Slush Rush
BookSprite: SRD-beartic-BookSprite.png
BoxSprite: SRD-beartic-BoxSprite.png
DexCategory: Freezing Pokemon
DexDescription: They the cold northern seas and create pathways across the ocean's
  water by freezing their own breath. They dive in the sea to catch prey. They are
  not used to humans as they rarely see one.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Cubchoo]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 8.5
  Meters: 2.6
HiddenAbility: Swift Swim
HomeSprite: SRD-beartic-HomeSprite.png
Image: beartic.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Icicle Crash|Icicle Crash]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Play Nice|Play Nice]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Avalanche|Avalanche]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
Number: 614
ShuffleToken: SRD-beartic-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 260.0
  Pounds: 573.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-beartic-BookSprite.png|wsmall]]
> ![[SRD-beartic-HomeSprite.png]]
> ![[SRD-beartic-BoxSprite.png|htiny]]
> ![[SRD-beartic-ShuffleToken.png|wsmall]]


*Freezing Pokemon*
*They the cold northern seas and create pathways across the ocean's water by freezing their own breath. They dive in the sea to catch prey. They are not used to humans as they rarely see one.*

**DexID**:: 0614
**Name**:: Beartic
**Type**:: Ice
**Abilities**:: [[SRD-Snow Cloak|Snow Cloak]] / [[SRD-Slush Rush|Slush Rush]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 8'5" / 2.6m
**Weight**: 573.2lbs / 260.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Cubchoo]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Beartic.md"
flatten moves as T
where file.path = this.file.path
```
