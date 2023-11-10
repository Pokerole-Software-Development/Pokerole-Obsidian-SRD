---
Ability1: Own Tempo
Ability2: Tangled Feet
BookSprite: SRD-spinda-BookSprite.png
BoxSprite: SRD-spinda-BoxSprite.png
DexCategory: Spot Panda Pokemon
DexDescription: Spindas move while stumbling in dizziness. This teeter dance causes
  a severe confusion on whoever is looking. They are shy towards humans but sometimes
  they appear in towns looking really disoriented.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Contrary
HomeSprite: SRD-spinda-HomeSprite.png
Image: spinda.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - Beginner
  - '[[SRD-Copycat|Copycat]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Dizzy Punch|Dizzy Punch]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Encore|Encore]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
Number: 327
ShuffleToken: SRD-spinda-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 5.0
  Pounds: 11.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-spinda-BookSprite.png|wsmall]]
> ![[SRD-spinda-HomeSprite.png]]
> ![[SRD-spinda-BoxSprite.png|htiny]]
> ![[SRD-spinda-ShuffleToken.png|wsmall]]


*Spot Panda Pokemon*
*Spindas move while stumbling in dizziness. This teeter dance causes a severe confusion on whoever is looking. They are shy towards humans but sometimes they appear in towns looking really disoriented.*

**DexID**:: 0327
**Name**:: Spinda
**Type**:: Normal
**Abilities**:: [[SRD-Own Tempo|Own Tempo]] / [[SRD-Tangled Feet|Tangled Feet]] ([[SRD-Contrary|Contrary]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 11.0lbs / 5.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Spinda.md"
flatten moves as T
where file.path = this.file.path
```
