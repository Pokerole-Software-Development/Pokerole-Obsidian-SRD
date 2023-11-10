---
Ability1: Flash Fire
Ability2: White Smoke
BookSprite: SRD-centiskorch-BookSprite.png
BoxSprite: SRD-centiskorch-BoxSprite.png
DexCategory: Radiator Pokemon
DexDescription: It lashes its body like a whip and launches itself at enemies, while
  its burning body is already dangerous on its own, this excessively hostile Pokemon
  also has large and very sharp fangs.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Sizzlipede]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 9.8
  Meters: 3.0
HiddenAbility: Flame Body
HomeSprite: SRD-centiskorch-HomeSprite.png
Image: centiskorch.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ember|Ember]]'
- - Starter
  - '[[SRD-Smokescreen|Smokescreen]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Wrap|Wrap]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Coil|Coil]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Fire Lash|Fire Lash]]'
- - Ace
  - '[[SRD-Lunge|Lunge]]'
- - Ace
  - '[[SRD-Burn Up|Burn Up]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Pro
  - '[[SRD-Scald|Scald]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
Number: 851
ShuffleToken: SRD-centiskorch-ShuffleToken.png
Type1: Fire
Type2: Bug
Weight:
  Kilograms: 120.0
  Pounds: 264.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-centiskorch-BookSprite.png|wsmall]]
> ![[SRD-centiskorch-HomeSprite.png]]
> ![[SRD-centiskorch-BoxSprite.png|htiny]]
> ![[SRD-centiskorch-ShuffleToken.png|wsmall]]


*Radiator Pokemon*
*It lashes its body like a whip and launches itself at enemies, while its burning body is already dangerous on its own, this excessively hostile Pokemon also has large and very sharp fangs.*

**DexID**:: 0851
**Name**:: Centiskorch
**Type**:: Fire / Bug
**Abilities**:: [[SRD-Flash Fire|Flash Fire]] / [[SRD-White Smoke|White Smoke]] ([[SRD-Flame Body|Flame Body]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 9'8" / 3.0m
**Weight**: 264.6lbs / 120.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Sizzlipede]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Centiskorch.md"
flatten moves as T
where file.path = this.file.path
```
