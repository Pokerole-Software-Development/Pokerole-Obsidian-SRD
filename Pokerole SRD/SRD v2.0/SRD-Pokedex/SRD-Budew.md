---
Ability1: Natural Cure
Ability2: Poison Point
BookSprite: SRD-budew-BookSprite.png
BoxSprite: SRD-budew-BoxSprite.png
DexCategory: Bud Pokemon
DexDescription: It blossoms near clear ponds. Budew needs nurturing and care to grow
  healthy and beautiful, otherwise its bud will never bloom. If threatened, they will
  reveal their small but poisonous thorns.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Roselia]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Leaf Guard
HomeSprite: SRD-budew-HomeSprite.png
Image: budew.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growth|Growth]]'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[SRD-Stun Spore|Stun Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Worry Seed|Worry Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 406
ShuffleToken: SRD-budew-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 1.2
  Pounds: 2.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-budew-BookSprite.png|wsmall]]
> ![[SRD-budew-HomeSprite.png]]
> ![[SRD-budew-BoxSprite.png|htiny]]
> ![[SRD-budew-ShuffleToken.png|wsmall]]


*Bud Pokemon*
*It blossoms near clear ponds. Budew needs nurturing and care to grow healthy and beautiful, otherwise its bud will never bloom. If threatened, they will reveal their small but poisonous thorns.*

**DexID**:: 0406
**Name**:: Budew
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Natural Cure|Natural Cure]] / [[SRD-Poison Point|Poison Point]] ([[SRD-Leaf Guard|Leaf Guard]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 0'7" / 0.2m
**Weight**: 2.6lbs / 1.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Stat      |   Value |
|:----------|:----------------|:-------|:----------|--------:|
| To        | [[SRD-Roselia]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Budew.md"
flatten moves as T
where file.path = this.file.path
```
