---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-dialga-BookSprite.png
BoxSprite: SRD-dialga-BoxSprite.png
DexCategory: No Data
DexDescription: "In some religions there is a being called \u201CThe God of Time\u201D\
  \ whose first roar brought future, present and past."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 17.7
  Meters: 5.4
HiddenAbility: Telepathy
HomeSprite: SRD-dialga-HomeSprite.png
Image: dialga.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slash|Slash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Power Gem|Power Gem]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Metal Burst|Metal Burst]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Claw|Dragon Claw]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Earth Power|Earth Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aura Sphere|Aura Sphere]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Tail|Iron Tail]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Roar Of Time|Roar Of Time]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flash Cannon|Flash Cannon]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psych Up|Psych Up]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trick Room|Trick Room]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
Number: 483
ShuffleToken: SRD-dialga-ShuffleToken.png
Type1: Steel
Type2: Dragon
Weight:
  Kilograms: 683.0
  Pounds: 1505.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dialga-BookSprite.png|wsmall]]
> ![[SRD-dialga-HomeSprite.png]]
> ![[SRD-dialga-BoxSprite.png|htiny]]
> ![[SRD-dialga-ShuffleToken.png|wsmall]]


*No Data*
*In some religions there is a being called “The God of Time” whose first roar brought future, present and past.*

**DexID**:: 0483
**Name**:: Dialga
**Type**:: Steel / Dragon
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::8)/(MaxSpecial::8)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 17'7" / 5.4m
**Weight**: 1505.8lbs / 683.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dialga.md"
flatten moves as T
where file.path = this.file.path
```
