---
Ability1: Flash Fire
Ability2: Flame Body
BookSprite: SRD-chandelure-BookSprite.png
BoxSprite: SRD-chandelure-BoxSprite.png
DexCategory: Luring Pokemon
DexDescription: It consumes the spirits of the living, puts people in a hypnotic trance
  and consumes them with fire. Being consumed in Chandelure's flame burns up the spirit,
  leaving only the body behind.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Dusk Stone
  Kind: Stone
  Pokemon: '[[SRD-Lampent]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Infiltrator
HomeSprite: SRD-chandelure-HomeSprite.png
Image: chandelure.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pain Split|Pain Split]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Power Split|Power Split]]'
- - Pro
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[SRD-Clear Smog|Clear Smog]]'
Number: 609
ShuffleToken: SRD-chandelure-ShuffleToken.png
Type1: Ghost
Type2: Fire
Weight:
  Kilograms: 34.3
  Pounds: 75.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-chandelure-BookSprite.png|wsmall]]
> ![[SRD-chandelure-HomeSprite.png]]
> ![[SRD-chandelure-BoxSprite.png|htiny]]
> ![[SRD-chandelure-ShuffleToken.png|wsmall]]


*Luring Pokemon*
*It consumes the spirits of the living, puts people in a hypnotic trance and consumes them with fire. Being consumed in Chandelure's flame burns up the spirit, leaving only the body behind.*

**DexID**:: 0609
**Name**:: Chandelure
**Type**:: Ghost / Fire
**Abilities**:: [[SRD-Flash Fire|Flash Fire]] / [[SRD-Flame Body|Flame Body]] ([[SRD-Infiltrator|Infiltrator]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 75.6lbs / 34.3kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon         | Kind   | Item       |
|:----------|:----------------|:-------|:-----------|
| From      | [[SRD-Lampent]] | Stone  | Dusk Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Chandelure.md"
flatten moves as T
where file.path = this.file.path
```
