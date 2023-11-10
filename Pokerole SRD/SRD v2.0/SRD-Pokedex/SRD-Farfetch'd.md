---
Ability1: Keen Eye
Ability2: Inner Focus
BookSprite: SRD-farfetchd-BookSprite.png
BoxSprite: SRD-farfetchd-BoxSprite.png
DexCategory: Wild Duck Pokemon
DexDescription: There used to be whole flocks of them in meadows near the lakes. Now
  they are almost extinct because their meat is delicious. They are fond of leeks
  and celery, they carry them around as sticks.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Defiant
HomeSprite: SRD-farfetchd-HomeSprite.png
Image: farfetchd.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Feint|Feint]]'
- - Ace
  - '[[SRD-False Swipe|False Swipe]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Pro
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Pro
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Pro
  - '[[SRD-Roost|Roost]]'
Number: 83
ShuffleToken: SRD-farfetchd-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 15.0
  Pounds: 33.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-farfetchd-BookSprite.png|wsmall]]
> ![[SRD-farfetchd-HomeSprite.png]]
> ![[SRD-farfetchd-BoxSprite.png|htiny]]
> ![[SRD-farfetchd-ShuffleToken.png|wsmall]]


*Wild Duck Pokemon*
*There used to be whole flocks of them in meadows near the lakes. Now they are almost extinct because their meat is delicious. They are fond of leeks and celery, they carry them around as sticks.*

**DexID**:: 0083
**Name**:: Farfetch'd
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Inner Focus|Inner Focus]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 33.1lbs / 15.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Farfetch'd.md"
flatten moves as T
where file.path = this.file.path
```
