---
Ability1: Thick Fat
Ability2: Hydration
BookSprite: SRD-dewgong-BookSprite.png
BoxSprite: SRD-dewgong-BoxSprite.png
DexCategory: Sea Lion Pokemon
DexDescription: "Its body is covered with a pure white fur. The colder the weather,\
  \ the more active it becomes. It hunts at night and it\u2019s excellent at catching\
  \ fish Pokemon. It is also very intelligent and playful."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Seel]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Ice Body
HomeSprite: SRD-dewgong-HomeSprite.png
Image: dewgong.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Avalanche|Avalanche]]'
- - Pro
  - '[[SRD-Perish Song|Perish Song]]'
- - Pro
  - '[[SRD-Horn Drill|Horn Drill]]'
Number: 87
ShuffleToken: SRD-dewgong-ShuffleToken.png
Type1: Water
Type2: Ice
Weight:
  Kilograms: 120.0
  Pounds: 264.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dewgong-BookSprite.png|wsmall]]
> ![[SRD-dewgong-HomeSprite.png]]
> ![[SRD-dewgong-BoxSprite.png|htiny]]
> ![[SRD-dewgong-ShuffleToken.png|wsmall]]


*Sea Lion Pokemon*
*Its body is covered with a pure white fur. The colder the weather, the more active it becomes. It hunts at night and it’s excellent at catching fish Pokemon. It is also very intelligent and playful.*

**DexID**:: 0087
**Name**:: Dewgong
**Type**:: Water / Ice
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Hydration|Hydration]] ([[SRD-Ice Body|Ice Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'6" / 1.7m
**Weight**: 264.6lbs / 120.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon      | Kind   | Speed   |
|:----------|:-------------|:-------|:--------|
| From      | [[SRD-Seel]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Dewgong.md"
flatten moves as T
where file.path = this.file.path
```
