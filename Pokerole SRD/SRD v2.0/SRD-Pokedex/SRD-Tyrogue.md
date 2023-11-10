---
Ability1: Guts
Ability2: Steadfast
BookSprite: SRD-tyrogue-BookSprite.png
BoxSprite: SRD-tyrogue-BoxSprite.png
DexCategory: Scuffle Pokemon
DexDescription: "Tyrogue is an energetic, competitive and fearless Pokemon that\u2019\
  s always looking to get stronger, fighting any enemies even if it looses. They attack\
  \ anyone, any day, anytime, everyday, without warning."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Hitmontop]]'
  Stat: Dexterity
  Value: -1
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Hitmonlee]]'
  Stat: Strength
  Value: -1
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Hitmonchan]]'
  Stat: Vitality
  Value: -1
GenderType: M
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Vital Spirit
HomeSprite: SRD-tyrogue-HomeSprite.png
Image: tyrogue.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Fake Out|Fake Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Work Up|Work Up]]'
- - Pro
  - '[[SRD-Role Play|Role Play]]'
- - Pro
  - '[[SRD-Seismic Toss|Seismic Toss]]'
Number: 236
ShuffleToken: SRD-tyrogue-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 21.0
  Pounds: 46.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tyrogue-BookSprite.png|wsmall]]
> ![[SRD-tyrogue-HomeSprite.png]]
> ![[SRD-tyrogue-BoxSprite.png|htiny]]
> ![[SRD-tyrogue-ShuffleToken.png|wsmall]]


*Scuffle Pokemon*
*Tyrogue is an energetic, competitive and fearless Pokemon that’s always looking to get stronger, fighting any enemies even if it looses. They attack anyone, any day, anytime, everyday, without warning.*

**DexID**:: 0236
**Name**:: Tyrogue
**Type**:: Fighting
**Abilities**:: [[SRD-Guts|Guts]] / [[SRD-Steadfast|Steadfast]] ([[SRD-Vital Spirit|Vital Spirit]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'3" / 0.7m
**Weight**: 46.3lbs / 21.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Stat      |   Value |
|:----------|:-------------------|:-------|:----------|--------:|
| To        | [[SRD-Hitmontop]]  | Stat   | Dexterity |      -1 |
| To        | [[SRD-Hitmonlee]]  | Stat   | Strength  |      -1 |
| To        | [[SRD-Hitmonchan]] | Stat   | Vitality  |      -1 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tyrogue.md"
flatten moves as T
where file.path = this.file.path
```
