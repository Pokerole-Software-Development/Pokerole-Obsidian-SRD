---
Ability1: Magician
Ability2: ''
BookSprite: SRD-hoopa-unbound-form-BookSprite.png
BoxSprite: SRD-hoopa-unbound-form-BoxSprite.png
DexCategory: No Data
DexDescription: There is a story of an old demon whose power unleashed horrors from
  other dimensions into earth, ripping the fabrics of existence, it opened portals
  to bring evil upon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Form
  Pokemon: '[[SRD-Hoopa]]'
GenderType: N
Height:
  Feet: 21.3
  Meters: 6.5
HiddenAbility: ''
HomeSprite: SRD-hoopa-unbound-form-HomeSprite.png
Image: hoopa-unbound-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Trick|Trick]]'
- - Master
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Master
  - '[[SRD-Ally Switch|Ally Switch]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Astonish|Astonish]]'
- - Master
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Master
  - '[[SRD-Light Screen|Light Screen]]'
- - Master
  - '[[SRD-Psybeam|Psybeam]]'
- - Master
  - '[[SRD-Skill Swap|Skill Swap]]'
- - Master
  - '[[SRD-Power Split|Power Split]]'
- - Master
  - '[[SRD-Guard Split|Guard Split]]'
- - Master
  - '[[SRD-Knock Off|Knock Off]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Master
  - '[[SRD-Trick Room|Trick Room]]'
- - Master
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Hyperspace Hole|Hyperspace Hole]]'
- - Master
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Master
  - '[[SRD-Magic Room|Magic Room]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Snatch|Snatch]]'
- - Master
  - '[[SRD-Throat Chop|Throat Chop]]'
Number: 720
ShuffleToken: SRD-hoopa-unbound-form-ShuffleToken.png
Type1: Psychic
Type2: Dark
Weight:
  Kilograms: 490.0
  Pounds: 1080.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hoopa-unbound-form-BookSprite.png|wsmall]]
> ![[SRD-hoopa-unbound-form-HomeSprite.png]]
> ![[SRD-hoopa-unbound-form-BoxSprite.png|htiny]]
> ![[SRD-hoopa-unbound-form-ShuffleToken.png|wsmall]]


*No Data*
*There is a story of an old demon whose power unleashed horrors from other dimensions into earth, ripping the fabrics of existence, it opened portals to bring evil upon.*

**DexID**:: 0720M1
**Name**:: Hoopa (Unbound Form)
**Type**:: Psychic / Dark
**Abilities**:: [[SRD-Magician|Magician]]
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::9)/(MaxSpecial::9)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 21'3" / 6.5m
**Weight**: 1080.3lbs / 490.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

| Evolves   | Pokemon       | Kind   |
|:----------|:--------------|:-------|
| From      | [[SRD-Hoopa]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Hoopa (Unbound Form).md"
flatten moves as T
where file.path = this.file.path
```
