---
Ability1: Bad Dreams
Ability2: ''
BookSprite: SRD-darkrai-BookSprite.png
BoxSprite: SRD-darkrai-BoxSprite.png
DexCategory: No Data
DexDescription: "All around the world, young children have depicted a similar figure\
  \ in their drawings. They call it \u201CThe Boogeyman\u201D. People say it will\
  \ make all your nightmares come true."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: ''
HomeSprite: SRD-darkrai-HomeSprite.png
Image: darkrai.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Master
  - '[[SRD-Disable|Disable]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Master
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Master
  - '[[SRD-Nightmare|Nightmare]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Haze|Haze]]'
- - Master
  - '[[SRD-Dark Void|Dark Void]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Master
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[SRD-Torment|Torment]]'
- - Master
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Master
  - '[[SRD-Foul Play|Foul Play]]'
- - Master
  - '[[SRD-Spite|Spite]]'
Number: 491
ShuffleToken: SRD-darkrai-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 50.5
  Pounds: 111.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-darkrai-BookSprite.png|wsmall]]
> ![[SRD-darkrai-HomeSprite.png]]
> ![[SRD-darkrai-BoxSprite.png|htiny]]
> ![[SRD-darkrai-ShuffleToken.png|wsmall]]


*No Data*
*All around the world, young children have depicted a similar figure in their drawings. They call it “The Boogeyman”. People say it will make all your nightmares come true.*

**DexID**:: 0491
**Name**:: Darkrai
**Type**:: Dark
**Abilities**:: [[SRD-Bad Dreams|Bad Dreams]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 111.3lbs / 50.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Darkrai.md"
flatten moves as T
where file.path = this.file.path
```
