---
Ability1: Hydration
Ability2: Sticky Hold
BookSprite: SRD-accelgor-BookSprite.png
BoxSprite: SRD-accelgor-BoxSprite.png
DexCategory: Shell Out Pokemon
DexDescription: Having removed its heavy shell, it becomes very light and swift. When
  its body dries out, it weakens. To prevent dehydration, it wraps itself in many
  layers of a thin membrane. It is very rare to see one in the wild.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Shelmet]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Unburden
HomeSprite: SRD-accelgor-HomeSprite.png
Image: accelgor.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Power Swap|Power Swap]]'
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Water Shuriken|Water Shuriken]]'
- - Beginner
  - '[[SRD-Double Team|Double Team]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Me First|Me First]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-U-Turn|U-Turn]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Pro
  - '[[SRD-Feint|Feint]]'
- - Pro
  - '[[SRD-Pursuit|Pursuit]]'
Number: 617
ShuffleToken: SRD-accelgor-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 25.3
  Pounds: 55.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-accelgor-BookSprite.png|wsmall]]
> ![[SRD-accelgor-HomeSprite.png]]
> ![[SRD-accelgor-BoxSprite.png|htiny]]
> ![[SRD-accelgor-ShuffleToken.png|wsmall]]


*Shell Out Pokemon*
*Having removed its heavy shell, it becomes very light and swift. When its body dries out, it weakens. To prevent dehydration, it wraps itself in many layers of a thin membrane. It is very rare to see one in the wild.*

**DexID**:: 0617
**Name**:: Accelgor
**Type**:: Bug
**Abilities**:: [[SRD-Hydration|Hydration]] / [[SRD-Sticky Hold|Sticky Hold]] ([[SRD-Unburden|Unburden]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::8) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 55.8lbs / 25.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Shelmet]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Accelgor.md"
flatten moves as T
where file.path = this.file.path
```
