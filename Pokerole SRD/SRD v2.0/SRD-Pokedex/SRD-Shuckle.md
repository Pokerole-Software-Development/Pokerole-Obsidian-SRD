---
Ability1: Sturdy
Ability2: Gluttony
BookSprite: SRD-shuckle-BookSprite.png
BoxSprite: SRD-shuckle-BoxSprite.png
DexCategory: Mold Pokemon
DexDescription: Shuckle is a very peaceful and patient gooey worm. The fluids secreted
  by its toes can make holes in rocks. It hides inside those hallow stones and wears
  them as a shell. It is known for storing berries inside.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Contrary
HomeSprite: SRD-shuckle-HomeSprite.png
Image: shuckle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bide|Bide]]'
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - Starter
  - '[[SRD-Rollout|Rollout]]'
- - Starter
  - '[[SRD-Sticky Web|Sticky Web]]'
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - Beginner
  - '[[SRD-Wrap|Wrap]]'
- - Beginner
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Amateur
  - '[[SRD-Power Trick|Power Trick]]'
- - Amateur
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Guard Split|Guard Split]]'
- - Ace
  - '[[SRD-Power Split|Power Split]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Infestation|Infestation]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Acupressure|Acupressure]]'
Number: 213
ShuffleToken: SRD-shuckle-ShuffleToken.png
Type1: Bug
Type2: Rock
Weight:
  Kilograms: 20.5
  Pounds: 45.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shuckle-BookSprite.png|wsmall]]
> ![[SRD-shuckle-HomeSprite.png]]
> ![[SRD-shuckle-BoxSprite.png|htiny]]
> ![[SRD-shuckle-ShuffleToken.png|wsmall]]


*Mold Pokemon*
*Shuckle is a very peaceful and patient gooey worm. The fluids secreted by its toes can make holes in rocks. It hides inside those hallow stones and wears them as a shell. It is known for storing berries inside.*

**DexID**:: 0213
**Name**:: Shuckle
**Type**:: Bug / Rock
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Gluttony|Gluttony]] ([[SRD-Contrary|Contrary]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::2)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::10)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::2)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::10)     |

**Height**: 2'0" / 0.6m
**Weight**: 45.2lbs / 20.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Shuckle.md"
flatten moves as T
where file.path = this.file.path
```
