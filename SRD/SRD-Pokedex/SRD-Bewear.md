---
Ability1: Fluffy
Ability2: Klutz
BookSprite: SRD-bewear-BookSprite.png
BoxSprite: SRD-bewear-BoxSprite.png
DexCategory: Strong Arm Pokemon
DexDescription: "They may look friendly but their brute strength makes them very dangerous.\
  \ Many Trainers have been severely injured and even snapped in half by the \u201C\
  hugs\u201D of a Bewear."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Stufful]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: Unnerve
HomeSprite: SRD-bewear-HomeSprite.png
Image: bewear.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - Beginner
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Bind|Bind]]'
- - Amateur
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Amateur
  - '[[SRD-Pain Split|Pain Split]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Pro
  - '[[SRD-Giga Impact|Giga Impact]]'
Number: 760
ShuffleToken: SRD-bewear-ShuffleToken.png
Type1: Normal
Type2: Fighting
Weight:
  Kilograms: 135.0
  Pounds: 297.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bewear-BookSprite.png|wsmall]]
> ![[SRD-bewear-HomeSprite.png]]
> ![[SRD-bewear-BoxSprite.png|htiny]]
> ![[SRD-bewear-ShuffleToken.png|wsmall]]


*Strong Arm Pokemon*
*They may look friendly but their brute strength makes them very dangerous. Many Trainers have been severely injured and even snapped in half by the “hugs” of a Bewear.*

**DexID**:: 0760
**Name**:: Bewear
**Type**:: Normal / Fighting
**Abilities**:: [[SRD-Fluffy|Fluffy]] / [[SRD-Klutz|Klutz]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 6'9" / 2.1m
**Weight**: 297.6lbs / 135.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Stufful]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Bewear.md"
flatten moves as T
where file.path = this.file.path
```
