---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-deoxys-attack-form-BookSprite.png
BoxSprite: SRD-deoxys-attack-form-BoxSprite.png
DexCategory: No Data
DexDescription: The main engineer of the space crew reported a tentacled creature
  that ripped with ease through the thick metal hull of the ship to escape. The ship
  was recovered and was indeed torn in two sections.
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
HomeSprite: SRD-deoxys-attack-form-HomeSprite.png
Image: deoxys-attack-form.png
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
  - '[[SRD-Taunt|Taunt]]'
- - Master
  - '[[SRD-Pursuit|Pursuit]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
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
ShuffleToken: SRD-deoxys-attack-form-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 60.8
  Pounds: 134.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-deoxys-attack-form-BookSprite.png|wsmall]]
> ![[SRD-deoxys-attack-form-HomeSprite.png]]
> ![[SRD-deoxys-attack-form-BoxSprite.png|htiny]]
> ![[SRD-deoxys-attack-form-ShuffleToken.png|wsmall]]


*No Data*
*The main engineer of the space crew reported a tentacled creature that ripped with ease through the thick metal hull of the ship to escape. The ship was recovered and was indeed torn in two sections.*

**DexID**:: 0386F1
**Name**:: Deoxys (Attack Form)
**Type**:: Psychic
**Abilities**:: [[SRD-Pressure|Pressure]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::10)/(MaxStrength::10)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 8)/(MaxDexterity::8) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::2)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::10)/(MaxSpecial::10)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::2)     |

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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Deoxys (Attack Form).md"
flatten moves as T
where file.path = this.file.path
```
