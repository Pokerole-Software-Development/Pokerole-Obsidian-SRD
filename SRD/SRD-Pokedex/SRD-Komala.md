---
Ability1: Comatose
Ability2: ''
BookSprite: SRD-komala-BookSprite.png
BoxSprite: SRD-komala-BoxSprite.png
DexCategory: Drowsing Pokemon
DexDescription: Komalas are born, live, and die asleep. They will have nightmares
  if you remove their log-pillow. Although it appears aware of its surroundings in
  reality it is just dreaming and reacting to the dream antics.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: ''
HomeSprite: SRD-komala-HomeSprite.png
Image: komala.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Starter
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Stockpile|Stockpile]]'
- - Beginner
  - '[[SRD-Spit Up|Spit Up]]'
- - Beginner
  - '[[SRD-Swallow|Swallow]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Psych Up|Psych Up]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Facade|Facade]]'
- - Pro
  - '[[SRD-Substitute|Substitute]]'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
Number: 775
ShuffleToken: SRD-komala-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 19.9
  Pounds: 43.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-komala-BookSprite.png|wsmall]]
> ![[SRD-komala-HomeSprite.png]]
> ![[SRD-komala-BoxSprite.png|htiny]]
> ![[SRD-komala-ShuffleToken.png|wsmall]]


*Drowsing Pokemon*
*Komalas are born, live, and die asleep. They will have nightmares if you remove their log-pillow. Although it appears aware of its surroundings in reality it is just dreaming and reacting to the dream antics.*

**DexID**:: 0775
**Name**:: Komala
**Type**:: Normal
**Abilities**:: [[SRD-Comatose|Comatose]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 1'3" / 0.4m
**Weight**: 43.9lbs / 19.9kg
**Good Starter**:: No
**Recommended Rank**:: Starter

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Komala.md"
flatten moves as T
where file.path = this.file.path
```
