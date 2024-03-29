---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-deoxys-speed-form-BookSprite.png
BoxSprite: SRD-deoxys-speed-form-BoxSprite.png
DexCategory: No Data
DexDescription: The First officer mentioned a slim creature that moved too fast for
  the radar to register and the eye to see. She saw it for a split second before it
  supposedly attacked the other end of the ship.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Deoxys]]'
GenderType: N
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-deoxys-speed-form-HomeSprite.png
Image: deoxys-speed-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wrap|Wrap]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Night Shade|Night Shade]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Teleport|Teleport]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Knock Off|Knock Off]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pursuit|Pursuit]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swift|Swift]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psycho Shift|Psycho Shift]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Recover|Recover]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psycho Boost|Psycho Boost]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Extreme Speed|Extreme Speed]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Toxic|Toxic]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bind|Bind]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Signal Beam|Signal Beam]]'
Number: 386
ShuffleToken: SRD-deoxys-speed-form-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 60.8
  Pounds: 134.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-deoxys-speed-form-BookSprite.png|wsmall]]
> ![[SRD-deoxys-speed-form-HomeSprite.png]]
> ![[SRD-deoxys-speed-form-BoxSprite.png|htiny]]
> ![[SRD-deoxys-speed-form-ShuffleToken.png|wsmall]]


*No Data*
*The First officer mentioned a slim creature that moved too fast for the radar to register and the eye to see. She saw it for a split second before it supposedly attacked the other end of the ship.*

**DexID**:: 0386F3
**Name**:: Deoxys (Speed Form)
**Type**:: Psychic
**Abilities**:: [[SRD-Pressure|Pressure]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 10)/(MaxDexterity::10) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 134.0lbs / 60.8kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon        | Kind   |
|:----------|:---------------|:-------|
| From      | [[SRD-Deoxys]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Deoxys (Speed Form).md"
flatten moves as T
where file.path = this.file.path
```
