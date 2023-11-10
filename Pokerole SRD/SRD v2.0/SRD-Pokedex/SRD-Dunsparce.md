---
Ability1: Serene Grace
Ability2: Run Away
BookSprite: SRD-dunsparce-BookSprite.png
BoxSprite: SRD-dunsparce-BoxSprite.png
DexCategory: Land Snake Pokemon
DexDescription: If seen, Dunsparce is quick to escape by boring into the ground with
  its drill tail. It can float slightly with its wings. It is almost blind but finds
  its way in the huge underground mazes where it lives.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Rattled
HomeSprite: SRD-dunsparce-HomeSprite.png
Image: dunsparce.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Starter
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - Beginner
  - '[[SRD-Spite|Spite]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Glare|Glare]]'
- - Amateur
  - '[[SRD-Coil|Coil]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Amateur
  - '[[SRD-Drill Run|Drill Run]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Roost|Roost]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Trump Card|Trump Card]]'
Number: 206
ShuffleToken: SRD-dunsparce-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 14.0
  Pounds: 30.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dunsparce-BookSprite.png|wsmall]]
> ![[SRD-dunsparce-HomeSprite.png]]
> ![[SRD-dunsparce-BoxSprite.png|htiny]]
> ![[SRD-dunsparce-ShuffleToken.png|wsmall]]


*Land Snake Pokemon*
*If seen, Dunsparce is quick to escape by boring into the ground with its drill tail. It can float slightly with its wings. It is almost blind but finds its way in the huge underground mazes where it lives.*

**DexID**:: 0206
**Name**:: Dunsparce
**Type**:: Normal
**Abilities**:: [[SRD-Serene Grace|Serene Grace]] / [[SRD-Run Away|Run Away]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'9" / 1.5m
**Weight**: 30.9lbs / 14.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dunsparce.md"
flatten moves as T
where file.path = this.file.path
```
