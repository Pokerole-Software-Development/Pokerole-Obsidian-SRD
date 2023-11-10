---
Ability1: Shield Dust
Ability2: Compound Eyes
BookSprite: SRD-vivillon-BookSprite.png
BoxSprite: SRD-vivillon-BoxSprite.png
DexCategory: Scale Pokemon
DexDescription: "The patterns on this Pokemon\u2019s wings depend on the climate it\
  \ grows and the flowers it feeds on. A famous Pokemon breeder made one develop a\
  \ Pokeball pattern, it was sold for a million dollars."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Spewpa]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Friend Guard
HomeSprite: SRD-vivillon-HomeSprite.png
Image: vivillon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Powder|Powder]]'
- - Starter
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Beginner
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Beginner
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
Number: 666
ShuffleToken: SRD-vivillon-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 17.0
  Pounds: 37.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-vivillon-BookSprite.png|wsmall]]
> ![[SRD-vivillon-HomeSprite.png]]
> ![[SRD-vivillon-BoxSprite.png|htiny]]
> ![[SRD-vivillon-ShuffleToken.png|wsmall]]


*Scale Pokemon*
*The patterns on this Pokemon’s wings depend on the climate it grows and the flowers it feeds on. A famous Pokemon breeder made one develop a Pokeball pattern, it was sold for a million dollars.*

**DexID**:: 0666
**Name**:: Vivillon
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Shield Dust|Shield Dust]] / [[SRD-Compound Eyes|Compound Eyes]] ([[SRD-Friend Guard|Friend Guard]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 37.5lbs / 17.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Spewpa]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Vivillon.md"
flatten moves as T
where file.path = this.file.path
```
