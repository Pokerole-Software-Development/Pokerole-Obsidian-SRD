---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-uxie-BookSprite.png
BoxSprite: SRD-uxie-BoxSprite.png
DexCategory: No Data
DexDescription: In the myths of Sinnoh they talk about three beings that came out
  from the same egg, the yellow one was the being of knowledge. Together they shaped
  the human race to be complete.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: ''
HomeSprite: SRD-uxie-HomeSprite.png
Image: uxie.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Memento|Memento]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Flail|Flail]]'
- - Master
  - '[[SRD-Rest|Rest]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Imprison|Imprison]]'
- - Master
  - '[[SRD-Endure|Endure]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Yawn|Yawn]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Amnesia|Amnesia]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Foul Play|Foul Play]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Trick Room|Trick Room]]'
- - Master
  - '[[SRD-Magic Room|Magic Room]]'
- - Master
  - '[[SRD-Wonder Room|Wonder Room]]'
Number: 480
ShuffleToken: SRD-uxie-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 0.3
  Pounds: 0.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-uxie-BookSprite.png|wsmall]]
> ![[SRD-uxie-HomeSprite.png]]
> ![[SRD-uxie-BoxSprite.png|htiny]]
> ![[SRD-uxie-ShuffleToken.png|wsmall]]


*No Data*
*In the myths of Sinnoh they talk about three beings that came out from the same egg, the yellow one was the being of knowledge. Together they shaped the human race to be complete.*

**DexID**:: 0480
**Name**:: Uxie
**Type**:: Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 1'0" / 0.3m
**Weight**: 0.7lbs / 0.3kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Uxie.md"
flatten moves as T
where file.path = this.file.path
```
