---
Ability1: Inner Focus
Ability2: Early Bird
BookSprite: SRD-girafarig-BookSprite.png
BoxSprite: SRD-girafarig-BoxSprite.png
DexCategory: Long Neck Pokemon
DexDescription: "Its tail is a head on its own, it bites if anything comes close and\
  \ never rests. Some say that the sum of its two heads grant it psychic powers. Even\
  \ if that\u2019s true, the tail isn\u2019t very bright, but it is quite vicious."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Sap Sipper
HomeSprite: SRD-girafarig-HomeSprite.png
Image: girafarig.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Astonish|Astonish]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confusion|Confusion]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growl|Growl]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Guard Swap|Guard Swap]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Power Swap|Power Swap]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Odor Sleuth|Odor Sleuth]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stomp|Stomp]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Baton Pass|Baton Pass]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Assurance|Assurance]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double Hit|Double Hit]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psychic|Psychic]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Future Sight|Future Sight]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Voice|Hyper Voice]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sucker Punch|Sucker Punch]]'
Number: 203
ShuffleToken: SRD-girafarig-ShuffleToken.png
Type1: Normal
Type2: Psychic
Weight:
  Kilograms: 41.5
  Pounds: 91.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-girafarig-BookSprite.png|wsmall]]
> ![[SRD-girafarig-HomeSprite.png]]
> ![[SRD-girafarig-BoxSprite.png|htiny]]
> ![[SRD-girafarig-ShuffleToken.png|wsmall]]


*Long Neck Pokemon*
*Its tail is a head on its own, it bites if anything comes close and never rests. Some say that the sum of its two heads grant it psychic powers. Even if that’s true, the tail isn’t very bright, but it is quite vicious.*

**DexID**:: 0203
**Name**:: Girafarig
**Type**:: Normal / Psychic
**Abilities**:: [[SRD-Inner Focus|Inner Focus]] / [[SRD-Early Bird|Early Bird]] ([[SRD-Sap Sipper|Sap Sipper]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'9" / 1.5m
**Weight**: 91.5lbs / 41.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Girafarig.md"
flatten moves as T
where file.path = this.file.path
```
