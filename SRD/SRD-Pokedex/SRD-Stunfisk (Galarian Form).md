---
Ability1: Mimicry
Ability2: ''
BookSprite: SRD-stunfisk-galarian-form-BookSprite.png
BoxSprite: SRD-stunfisk-galarian-form-BoxSprite.png
DexCategory: Trap Pokemon
DexDescription: "Stunfisk lives in mud with high iron content. Those nutrients turned\
  \ its body into a Steel Type. Stunfisks\u2019 lips are hard to spot in the mud,\
  \ but if someone steps on it, its jagged steel clamps their prey."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: ''
HomeSprite: SRD-stunfisk-galarian-form-HomeSprite.png
Image: stunfisk-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Mud Slap|Mud Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Beginner
  - '[[SRD-Endure|Endure]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Bounce|Bounce]]'
- - Amateur
  - '[[SRD-Muddy Water|Muddy Water]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Snap Trap|Snap Trap]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Bind|Bind]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
Number: 618
ShuffleToken: SRD-stunfisk-galarian-form-ShuffleToken.png
Type1: Ground
Type2: Steel
Weight:
  Kilograms: 20.5
  Pounds: 45.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-stunfisk-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-stunfisk-galarian-form-HomeSprite.png]]
> ![[SRD-stunfisk-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-stunfisk-galarian-form-ShuffleToken.png|wsmall]]


*Trap Pokemon*
*Stunfisk lives in mud with high iron content. Those nutrients turned its body into a Steel Type. Stunfisks’ lips are hard to spot in the mud, but if someone steps on it, its jagged steel clamps their prey.*

**DexID**:: 0618G
**Name**:: Stunfisk (Galarian Form)
**Type**:: Ground / Steel
**Abilities**:: [[SRD-Mimicry|Mimicry]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 45.2lbs / 20.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Stunfisk (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
