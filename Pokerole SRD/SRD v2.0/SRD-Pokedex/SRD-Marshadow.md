---
Ability1: Technician
Ability2: ''
BookSprite: SRD-marshadow-BookSprite.png
BoxSprite: SRD-marshadow-BoxSprite.png
DexCategory: No Data
DexDescription: "There is an old children\u2019s story about a boy who lost his shadow\
  \ and the shadow became a Pokemon. It is debated which Pokemon the story is making\
  \ mention of."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: ''
HomeSprite: SRD-marshadow-HomeSprite.png
Image: marshadow.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Assurance|Assurance]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Punch|Fire Punch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ice Punch|Ice Punch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Punch|Thunder Punch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Drain Punch|Drain Punch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Counter|Counter]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pursuit|Pursuit]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Sneak|Shadow Sneak]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Force Palm|Force Palm]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Feint|Feint]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rolling Kick|Rolling Kick]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Copycat|Copycat]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shadow Punch|Shadow Punch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Role Play|Role Play]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Jump Kick|Jump Kick]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psych Up|Psych Up]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spectral Thief|Spectral Thief]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Close Combat|Close Combat]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sucker Punch|Sucker Punch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endeavor|Endeavor]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Throat Chop|Throat Chop]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Jab|Poison Jab]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Superpower|Superpower]]'
Number: 802
ShuffleToken: SRD-marshadow-ShuffleToken.png
Type1: Fighting
Type2: Ghost
Weight:
  Kilograms: 22.2
  Pounds: 48.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-marshadow-BookSprite.png|wsmall]]
> ![[SRD-marshadow-HomeSprite.png]]
> ![[SRD-marshadow-BoxSprite.png|htiny]]
> ![[SRD-marshadow-ShuffleToken.png|wsmall]]


*No Data*
*There is an old children’s story about a boy who lost his shadow and the shadow became a Pokemon. It is debated which Pokemon the story is making mention of.*

**DexID**:: 0802
**Name**:: Marshadow
**Type**:: Fighting / Ghost
**Abilities**:: [[SRD-Technician|Technician]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 48.9lbs / 22.2kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Marshadow.md"
flatten moves as T
where file.path = this.file.path
```
