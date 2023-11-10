---
Ability1: Limber
Ability2: Reckless
BookSprite: SRD-hitmonlee-BookSprite.png
BoxSprite: SRD-hitmonlee-BoxSprite.png
DexCategory: Kicking Pokemon
DexDescription: Kicking Pokemon Its legs freely stretch and contract. It bowls over
  foes with devastating kicks. It is very disciplined and trains every day. It is
  very rare in the wild, and it is mostly found in urban areas
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Tyrogue]]'
  Stat: Strength
  Value: -1
GenderType: M
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Unburden
HomeSprite: SRD-hitmonlee-HomeSprite.png
Image: hitmonlee.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Double Kick|Double Kick]]'
- - Starter
  - '[[SRD-Revenge|Revenge]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Meditate|Meditate]]'
- - Beginner
  - '[[SRD-Rolling Kick|Rolling Kick]]'
- - Beginner
  - '[[SRD-Jump Kick|Jump Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Amateur
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Amateur
  - '[[SRD-Foresight|Foresight]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Amateur
  - '[[SRD-Blaze Kick|Blaze Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Endure|Endure]]'
- - Ace
  - '[[SRD-Mega Kick|Mega Kick]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Pro
  - '[[SRD-Mach Punch|Mach Punch]]'
Number: 106
ShuffleToken: SRD-hitmonlee-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 49.8
  Pounds: 109.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hitmonlee-BookSprite.png|wsmall]]
> ![[SRD-hitmonlee-HomeSprite.png]]
> ![[SRD-hitmonlee-BoxSprite.png|htiny]]
> ![[SRD-hitmonlee-ShuffleToken.png|wsmall]]


*Kicking Pokemon*
*Kicking Pokemon Its legs freely stretch and contract. It bowls over foes with devastating kicks. It is very disciplined and trains every day. It is very rare in the wild, and it is mostly found in urban areas*

**DexID**:: 0106
**Name**:: Hitmonlee
**Type**:: Fighting
**Abilities**:: [[SRD-Limber|Limber]] / [[SRD-Reckless|Reckless]] ([[SRD-Unburden|Unburden]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 109.8lbs / 49.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Stat     |   Value |
|:----------|:----------------|:-------|:---------|--------:|
| From      | [[SRD-Tyrogue]] | Stat   | Strength |      -1 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Hitmonlee.md"
flatten moves as T
where file.path = this.file.path
```
