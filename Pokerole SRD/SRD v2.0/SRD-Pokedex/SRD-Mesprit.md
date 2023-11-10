---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-mesprit-BookSprite.png
BoxSprite: SRD-mesprit-BoxSprite.png
DexCategory: No Data
DexDescription: In the myths of Sinnoh they talk about three beings that came out
  from the same egg, the pink one was the being of emotion. Together they shaped the
  human race to be complete.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: ''
HomeSprite: SRD-mesprit-HomeSprite.png
Image: mesprit.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Copycat|Copycat]]'
- - Master
  - '[[SRD-Rest|Rest]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Imprison|Imprison]]'
- - Master
  - '[[SRD-Protect|Protect]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Charm|Charm]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Role Play|Role Play]]'
- - Master
  - '[[SRD-Knock Off|Knock Off]]'
- - Master
  - '[[SRD-Trick|Trick]]'
Number: 481
ShuffleToken: SRD-mesprit-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 0.3
  Pounds: 0.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mesprit-BookSprite.png|wsmall]]
> ![[SRD-mesprit-HomeSprite.png]]
> ![[SRD-mesprit-BoxSprite.png|htiny]]
> ![[SRD-mesprit-ShuffleToken.png|wsmall]]


*No Data*
*In the myths of Sinnoh they talk about three beings that came out from the same egg, the pink one was the being of emotion. Together they shaped the human race to be complete.*

**DexID**:: 0481
**Name**:: Mesprit
**Type**:: Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

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
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mesprit.md"
flatten moves as T
where file.path = this.file.path
```
