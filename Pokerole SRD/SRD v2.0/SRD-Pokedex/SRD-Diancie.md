---
Ability1: Clear Body
Ability2: ''
BookSprite: SRD-diancie-BookSprite.png
BoxSprite: SRD-diancie-BoxSprite.png
DexCategory: 'Registered as #703 Carbink'
DexDescription: "The popular saying goes like this: \u201CIf you put a Carbon under\
  \ pressure you will get a Diamond\u201D But it surely was not referring to a Pokemon...\
  \ or was it?"
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Diancite
  Kind: Mega
  Pokemon: '[[SRD-Diancie (Mega Form)]]'
GenderType: N
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: ''
HomeSprite: SRD-diancie-HomeSprite.png
Image: diancie.png
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
ShuffleToken: SRD-diancie-ShuffleToken.png
Type1: Rock
Type2: Fairy
Weight:
  Kilograms: 8.8
  Pounds: 19.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-diancie-BookSprite.png|wsmall]]
> ![[SRD-diancie-HomeSprite.png]]
> ![[SRD-diancie-BoxSprite.png|htiny]]
> ![[SRD-diancie-ShuffleToken.png|wsmall]]


*Registered as #703 Carbink*
*The popular saying goes like this: “If you put a Carbon under pressure you will get a Diamond” But it surely was not referring to a Pokemon... or was it?*

**DexID**:: 0719
**Name**:: Diancie
**Type**:: Rock / Fairy
**Abilities**:: [[SRD-Clear Body|Clear Body]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::8)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::8)/(MaxInsight::8)     |

**Height**: 2'3" / 0.7m
**Weight**: 19.4lbs / 8.8kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon                     | Kind   | Item     |
|:----------|:----------------------------|:-------|:---------|
| To        | [[SRD-Diancie (Mega Form)]] | Mega   | Diancite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Diancie.md"
flatten moves as T
where file.path = this.file.path
```
