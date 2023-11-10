---
Ability1: Hustle
Ability2: Serene Grace
BookSprite: SRD-togepi-BookSprite.png
BoxSprite: SRD-togepi-BoxSprite.png
DexCategory: Spike Ball Pokemon
DexDescription: "This Pokemon stores all the kindness and good feelings inside of\
  \ it\u2019s shell and shares them with others, when the shell is full it becomes\
  \ so happy that it finally evolves. It is said that it\u2019ll bring good fortune\
  \ to its trainer."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Togetic]]'
  Stat: Happiness
  Value: 5
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Super Luck
HomeSprite: SRD-togepi-HomeSprite.png
Image: togepi.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Charm|Charm]]'
- - Beginner
  - '[[SRD-Metronome|Metronome]]'
- - Beginner
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Follow Me|Follow Me]]'
- - Amateur
  - '[[SRD-Bestow|Bestow]]'
- - Amateur
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wish|Wish]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-After You|After You]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
Number: 175
ShuffleToken: SRD-togepi-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 1.5
  Pounds: 3.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-togepi-BookSprite.png|wsmall]]
> ![[SRD-togepi-HomeSprite.png]]
> ![[SRD-togepi-BoxSprite.png|htiny]]
> ![[SRD-togepi-ShuffleToken.png|wsmall]]


*Spike Ball Pokemon*
*This Pokemon stores all the kindness and good feelings inside of it’s shell and shares them with others, when the shell is full it becomes so happy that it finally evolves. It is said that it’ll bring good fortune to its trainer.*

**DexID**:: 0175
**Name**:: Togepi
**Type**:: Fairy
**Abilities**:: [[SRD-Hustle|Hustle]] / [[SRD-Serene Grace|Serene Grace]] ([[SRD-Super Luck|Super Luck]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 3.3lbs / 1.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Stat      |   Value |
|:----------|:----------------|:-------|:----------|--------:|
| To        | [[SRD-Togetic]] | Stat   | Happiness |       5 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Togepi.md"
flatten moves as T
where file.path = this.file.path
```
