---
Ability1: Beast Boost
Ability2: ''
BookSprite: SRD-blacephalon-BookSprite.png
BoxSprite: SRD-blacephalon-BoxSprite.png
DexCategory: 'Aether Foundation Log #121'
DexDescription: It was horrible and so fast I could barely take a picture of the UB
  specimen. As soon as the portal opened it slithered through it, got close to one
  of the team members and exploded. His state is critical, the UB disappeared.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: ''
HomeSprite: SRD-blacephalon-HomeSprite.png
Image: blacephalon.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ember|Ember]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Astonish|Astonish]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magic Coat|Magic Coat]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stored Power|Stored Power]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flame Burst|Flame Burst]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Night Shade|Night Shade]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Light Screen|Light Screen]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Blast|Fire Blast]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Ball|Shadow Ball]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trick|Trick]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mind Blown|Mind Blown]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Explosion|Explosion]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spite|Spite]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heat Wave|Heat Wave]]'
Number: 806
ShuffleToken: SRD-blacephalon-ShuffleToken.png
Type1: Fire
Type2: Ghost
Weight:
  Kilograms: 13.0
  Pounds: 28.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-blacephalon-BookSprite.png|wsmall]]
> ![[SRD-blacephalon-HomeSprite.png]]
> ![[SRD-blacephalon-BoxSprite.png|htiny]]
> ![[SRD-blacephalon-ShuffleToken.png|wsmall]]


*Aether Foundation Log #121*
*It was horrible and so fast I could barely take a picture of the UB specimen. As soon as the portal opened it slithered through it, got close to one of the team members and exploded. His state is critical, the UB disappeared.*

**DexID**:: 0806
**Name**:: Blacephalon
**Type**:: Fire / Ghost
**Abilities**:: [[SRD-Beast Boost|Beast Boost]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 28.7lbs / 13.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Blacephalon.md"
flatten moves as T
where file.path = this.file.path
```
