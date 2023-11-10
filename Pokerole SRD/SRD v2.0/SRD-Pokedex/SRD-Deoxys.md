---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-deoxys-BookSprite.png
BoxSprite: SRD-deoxys-BoxSprite.png
DexCategory: No Data
DexDescription: "A space expedition had to be aborted due to an emergency. The ship\u2019\
  s crew mentioned a creature attacking them inside their ship. They all gave different\
  \ descriptions of said creature."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Deoxys (Attack Form)]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Deoxys (Defense Form)]]'
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Deoxys (Speed Form)]]'
GenderType: N
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-deoxys-HomeSprite.png
Image: deoxys.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Wrap|Wrap]]'
- - Master
  - '[[SRD-Night Shade|Night Shade]]'
- - Master
  - '[[SRD-Teleport|Teleport]]'
- - Master
  - '[[SRD-Knock Off|Knock Off]]'
- - Master
  - '[[SRD-Pursuit|Pursuit]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Snatch|Snatch]]'
- - Master
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Psycho Boost|Psycho Boost]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Toxic|Toxic]]'
- - Master
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[SRD-Bind|Bind]]'
- - Master
  - '[[SRD-Signal Beam|Signal Beam]]'
Number: 386
ShuffleToken: SRD-deoxys-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 60.8
  Pounds: 134.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-deoxys-BookSprite.png|wsmall]]
> ![[SRD-deoxys-HomeSprite.png]]
> ![[SRD-deoxys-BoxSprite.png|htiny]]
> ![[SRD-deoxys-ShuffleToken.png|wsmall]]


*No Data*
*A space expedition had to be aborted due to an emergency. The ship’s crew mentioned a creature attacking them inside their ship. They all gave different descriptions of said creature.*

**DexID**:: 0386
**Name**:: Deoxys
**Type**:: Psychic
**Abilities**:: [[SRD-Pressure|Pressure]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 8)/(MaxDexterity::8) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::4)/(MaxInsight::4)     |

**Height**: 5'6" / 1.7m
**Weight**: 134.0lbs / 60.8kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon                       | Kind   |
|:----------|:------------------------------|:-------|
| To        | [[SRD-Deoxys (Attack Form)]]  | Form   |
| To        | [[SRD-Deoxys (Defense Form)]] | Form   |
| To        | [[SRD-Deoxys (Speed Form)]]   | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Deoxys.md"
flatten moves as T
where file.path = this.file.path
```
