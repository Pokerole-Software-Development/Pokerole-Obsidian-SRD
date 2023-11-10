---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-unown-BookSprite.png
BoxSprite: SRD-unown-BoxSprite.png
DexCategory: Symbol Pokemon
DexDescription: There are depictions of it in ancient ruins. When Unowns are gathered
  together, it is said that a strange power capable of anything emerges. They are
  all shaped like letters, each one of them with a unique power.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: ''
HomeSprite: SRD-unown-HomeSprite.png
Image: unown.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Hidden Power|Hidden Power]]'
Number: 201
ShuffleToken: SRD-unown-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 5.0
  Pounds: 11.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-unown-BookSprite.png|wsmall]]
> ![[SRD-unown-HomeSprite.png]]
> ![[SRD-unown-BoxSprite.png|htiny]]
> ![[SRD-unown-ShuffleToken.png|wsmall]]


*Symbol Pokemon*
*There are depictions of it in ancient ruins. When Unowns are gathered together, it is said that a strange power capable of anything emerges. They are all shaped like letters, each one of them with a unique power.*

**DexID**:: 0201
**Name**:: Unown
**Type**:: Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 11.0lbs / 5.0kg
**Good Starter**:: No
**Recommended Rank**:: Starter

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Unown.md"
flatten moves as T
where file.path = this.file.path
```
