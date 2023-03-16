---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-azelf-BookSprite.png
BoxSprite: SRD-azelf-BoxSprite.png
DexCategory: No Data
DexDescription: In the myths of Sinnoh they talk about three beings that came out
  from the same egg, the blue one was the being of willpower. Together they shaped
  the human race to be complete.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: ''
HomeSprite: SRD-azelf-HomeSprite.png
Image: azelf.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Last Resort|Last Resort]]'
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
  - '[[SRD-Detect|Detect]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Uproar|Uproar]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Explosion|Explosion]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Master
  - '[[SRD-Skill Swap|Skill Swap]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
Number: 482
ShuffleToken: SRD-azelf-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 0.3
  Pounds: 0.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-azelf-BookSprite.png|wsmall]]
> ![[SRD-azelf-HomeSprite.png]]
> ![[SRD-azelf-BoxSprite.png|htiny]]
> ![[SRD-azelf-ShuffleToken.png|wsmall]]


*No Data*
*In the myths of Sinnoh they talk about three beings that came out from the same egg, the blue one was the being of willpower. Together they shaped the human race to be complete.*

**DexID**:: 0482
**Name**:: Azelf
**Type**:: Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

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
FROM "SRD/SRD-Pokedex/SRD-Azelf.md"
flatten moves as T
where file.path = this.file.path
```
