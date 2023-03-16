---
Ability1: Competitive
Ability2: ''
BookSprite: SRD-articuno-galarian-form-BookSprite.png
BoxSprite: SRD-articuno-galarian-form-BoxSprite.png
DexCategory: ''
DexDescription: ''
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: ''
HomeSprite: SRD-articuno-galarian-form-HomeSprite.png
Image: articuno-galarian-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Gust|Gust]]'
- - Master
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Freezing Glare|Freezing Glare]]'
- - Master
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Trick Room|Trick Room]]'
- - Master
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Master
  - '[[SRD-Expanding Force|Expanding Force]]'
- - Master
  - '[[SRD-Fly|Fly]]'
Number: 144
ShuffleToken: SRD-articuno-galarian-form-ShuffleToken.png
Type1: Psychic
Type2: Flying
Weight:
  Kilograms: 50.9
  Pounds: 112.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-articuno-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-articuno-galarian-form-HomeSprite.png]]
> ![[SRD-articuno-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-articuno-galarian-form-ShuffleToken.png|wsmall]]


**
**

**DexID**:: 0144G
**Name**:: Articuno (Galarian Form)
**Type**:: Psychic / Flying
**Abilities**:: [[SRD-Competitive|Competitive]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 5'6" / 1.7m
**Weight**: 112.2lbs / 50.9kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Articuno (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
