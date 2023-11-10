---
Ability1: Oblivious
Ability2: Tinted Lens
BookSprite: SRD-illumise-BookSprite.png
BoxSprite: SRD-illumise-BoxSprite.png
DexCategory: Firelfy Pokemon
DexDescription: They attract swarms of Volbeat with their sweet fragrance and organize
  the swarm into drawing geometric shapes made of light. Illumises gain rank in their
  group if they make an amazing performance.
EventAbilities: ''
Evolutions: []
GenderType: F
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Prankster
HomeSprite: SRD-illumise-HomeSprite.png
Image: illumise.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Beginner
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Moonlight|Moonlight]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - Amateur
  - '[[SRD-Wish|Wish]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Flatter|Flatter]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[SRD-Covet|Covet]]'
- - Ace
  - '[[SRD-Infestation|Infestation]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Captivate|Captivate]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[SRD-Silver Wind|Silver Wind]]'
Number: 314
ShuffleToken: SRD-illumise-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 17.7
  Pounds: 39.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-illumise-BookSprite.png|wsmall]]
> ![[SRD-illumise-HomeSprite.png]]
> ![[SRD-illumise-BoxSprite.png|htiny]]
> ![[SRD-illumise-ShuffleToken.png|wsmall]]


*Firelfy Pokemon*
*They attract swarms of Volbeat with their sweet fragrance and organize the swarm into drawing geometric shapes made of light. Illumises gain rank in their group if they make an amazing performance.*

**DexID**:: 0314
**Name**:: Illumise
**Type**:: Bug
**Abilities**:: [[SRD-Oblivious|Oblivious]] / [[SRD-Tinted Lens|Tinted Lens]] ([[SRD-Prankster|Prankster]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 39.0lbs / 17.7kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Illumise.md"
flatten moves as T
where file.path = this.file.path
```
