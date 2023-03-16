---
Ability1: Magic Bounce
Ability2: ''
BookSprite: SRD-diancie-mega-form-BookSprite.png
BoxSprite: SRD-diancie-mega-form-BoxSprite.png
DexCategory: 'Registered as #703 Carbink'
DexDescription: "The popular saying goes like this: \u201CIf you put a Carbon under\
  \ pressure you will get a Diamond\u201D But it surely was not referring to a Pokemon...\
  \ or was it?"
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Diancite
  Kind: Mega
  Pokemon: '[[SRD-Diancie]]'
GenderType: N
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: ''
HomeSprite: SRD-diancie-mega-form-HomeSprite.png
Image: diancie-mega-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Tackle|Tackle]]'
- - Master
  - '[[SRD-Harden|Harden]]'
- - Master
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Master
  - '[[SRD-Sharpen|Sharpen]]'
- - Master
  - '[[SRD-Smack Down|Smack Down]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Master
  - '[[SRD-Guard Split|Guard Split]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Flail|Flail]]'
- - Master
  - '[[SRD-Skill Swap|Skill Swap]]'
- - Master
  - '[[SRD-Power Gem|Power Gem]]'
- - Master
  - '[[SRD-Trick Room|Trick Room]]'
- - Master
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Diamond Storm|Diamond Storm]]'
- - Master
  - '[[SRD-Light Screen|Light Screen]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
Number: 719
ShuffleToken: SRD-diancie-mega-form-ShuffleToken.png
Type1: Rock
Type2: Fairy
Weight:
  Kilograms: 27.8
  Pounds: 61.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-diancie-mega-form-BookSprite.png|wsmall]]
> ![[SRD-diancie-mega-form-HomeSprite.png]]
> ![[SRD-diancie-mega-form-BoxSprite.png|htiny]]
> ![[SRD-diancie-mega-form-ShuffleToken.png|wsmall]]


*Registered as #703 Carbink*
*The popular saying goes like this: “If you put a Carbon under pressure you will get a Diamond” But it surely was not referring to a Pokemon... or was it?*

**DexID**:: 0719M1
**Name**:: Diancie (Mega Form)
**Type**:: Rock / Fairy
**Abilities**:: [[SRD-Magic Bounce|Magic Bounce]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 3'6" / 1.1m
**Weight**: 61.3lbs / 27.8kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon         | Kind   | Item     |
|:----------|:----------------|:-------|:---------|
| From      | [[SRD-Diancie]] | Mega   | Diancite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Diancie (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
