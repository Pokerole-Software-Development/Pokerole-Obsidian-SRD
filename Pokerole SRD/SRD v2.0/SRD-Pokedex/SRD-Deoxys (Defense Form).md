---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-deoxys-defense-form-BookSprite.png
BoxSprite: SRD-deoxys-defense-form-BoxSprite.png
DexCategory: No Data
DexDescription: "One member of the space crew mentioned a broad creature that could\
  \ reflect their weapon\u2019s attacks back at them. There was an explosion and the\
  \ creature left, unscathed."
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
HomeSprite: SRD-deoxys-defense-form-HomeSprite.png
Image: deoxys-defense-form.png
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
  - '[[SRD-Spikes|Spikes]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Snatch|Snatch]]'
- - Master
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Amnesia|Amnesia]]'
- - Master
  - '[[SRD-Psycho Boost|Psycho Boost]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Counter|Counter]]'
- - Master
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Master
  - '[[SRD-Bind|Bind]]'
- - Master
  - '[[SRD-Signal Beam|Signal Beam]]'
Number: 386
ShuffleToken: SRD-deoxys-defense-form-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 60.8
  Pounds: 134.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-deoxys-defense-form-BookSprite.png|wsmall]]
> ![[SRD-deoxys-defense-form-HomeSprite.png]]
> ![[SRD-deoxys-defense-form-BoxSprite.png|htiny]]
> ![[SRD-deoxys-defense-form-ShuffleToken.png|wsmall]]


*No Data*
*One member of the space crew mentioned a broad creature that could reflect their weapon’s attacks back at them. There was an explosion and the creature left, unscathed.*

**DexID**:: 0386F2
**Name**:: Deoxys (Defense Form)
**Type**:: Psychic
**Abilities**:: [[SRD-Pressure|Pressure]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::9)/(MaxVitality::9)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::9)/(MaxInsight::9)     |

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
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Deoxys (Defense Form).md"
flatten moves as T
where file.path = this.file.path
```
