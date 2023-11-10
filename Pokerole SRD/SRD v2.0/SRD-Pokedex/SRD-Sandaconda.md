---
Ability1: Sand Spit
Ability2: Shed Skin
BookSprite: SRD-sandaconda-BookSprite.png
BoxSprite: SRD-sandaconda-BoxSprite.png
DexCategory: Sand Snake Pokemon
DexDescription: It has a sack that can carry up to 220 lbs of sand, the way it coils
  allow it to spray the sand to its foes. If it sack ever runs out of sand it becomes
  limp and depressed. They are unfriendly but not really aggressive.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Silicobra]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 12.5
  Meters: 3.8
HiddenAbility: Sand Veil
HomeSprite: SRD-sandaconda-HomeSprite.png
Image: sandaconda.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[SRD-Skull Bash|Skull Bash]]'
- - Beginner
  - '[[SRD-Wrap|Wrap]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Glare|Glare]]'
- - Ace
  - '[[SRD-Dig|Dig]]'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Slam|Slam]]'
- - Ace
  - '[[SRD-Coil|Coil]]'
- - Ace
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hurricane|Hurricane]]'
- - Pro
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Pro
  - '[[SRD-Giga Impact|Giga Impact]]'
Number: 844
ShuffleToken: SRD-sandaconda-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 65.5
  Pounds: 144.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sandaconda-BookSprite.png|wsmall]]
> ![[SRD-sandaconda-HomeSprite.png]]
> ![[SRD-sandaconda-BoxSprite.png|htiny]]
> ![[SRD-sandaconda-ShuffleToken.png|wsmall]]


*Sand Snake Pokemon*
*It has a sack that can carry up to 220 lbs of sand, the way it coils allow it to spray the sand to its foes. If it sack ever runs out of sand it becomes limp and depressed. They are unfriendly but not really aggressive.*

**DexID**:: 0844
**Name**:: Sandaconda
**Type**:: Ground
**Abilities**:: [[SRD-Sand Spit|Sand Spit]] / [[SRD-Shed Skin|Shed Skin]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 12'5" / 3.8m
**Weight**: 144.4lbs / 65.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Silicobra]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sandaconda.md"
flatten moves as T
where file.path = this.file.path
```
