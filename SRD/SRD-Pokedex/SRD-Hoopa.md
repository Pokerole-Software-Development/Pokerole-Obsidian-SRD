---
Ability1: Magician
Ability2: ''
BookSprite: SRD-hoopa-BookSprite.png
BoxSprite: SRD-hoopa-BoxSprite.png
DexCategory: No Data
DexDescription: There is a story of an old demon whose power had to be contained by
  a spell. The spell was a partial success as the demon could still roam free, but
  its power and evil was greatly diminished.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Form
  Pokemon: '[[SRD-Hoopa (Unbound Form)]]'
GenderType: N
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: ''
HomeSprite: SRD-hoopa-HomeSprite.png
Image: hoopa.png
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
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Master
  - '[[SRD-Trick Room|Trick Room]]'
- - Master
  - '[[SRD-Shadow Ball|Shadow Ball]]'
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
  - '[[SRD-Confide|Confide]]'
Number: 720
ShuffleToken: SRD-hoopa-ShuffleToken.png
Type1: Psychic
Type2: Ghost
Weight:
  Kilograms: 9.0
  Pounds: 19.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hoopa-BookSprite.png|wsmall]]
> ![[SRD-hoopa-HomeSprite.png]]
> ![[SRD-hoopa-BoxSprite.png|htiny]]
> ![[SRD-hoopa-ShuffleToken.png|wsmall]]


*No Data*
*There is a story of an old demon whose power had to be contained by a spell. The spell was a partial success as the demon could still roam free, but its power and evil was greatly diminished.*

**DexID**:: 0720
**Name**:: Hoopa
**Type**:: Psychic / Ghost
**Abilities**:: [[SRD-Magician|Magician]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 1'6" / 0.5m
**Weight**: 19.8lbs / 9.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon                      | Kind   |
|:----------|:-----------------------------|:-------|
| To        | [[SRD-Hoopa (Unbound Form)]] | Form   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Hoopa.md"
flatten moves as T
where file.path = this.file.path
```
