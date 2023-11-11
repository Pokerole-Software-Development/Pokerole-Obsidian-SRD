---
Ability1: Keen Eye
Ability2: Tangled Feet
BookSprite: SRD-chatot-BookSprite.png
BoxSprite: SRD-chatot-BoxSprite.png
DexCategory: Music Note Pokemon
DexDescription: "It mimics the cries of other Pokemon to trick them into thinking\
  \ it\u2019s one of them, this way they won\u2019t attack it. Chatots that live with\
  \ humans learn words and phrases but it\u2019s unknown it they really know their\
  \ meaning."
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Big Pecks
HomeSprite: SRD-chatot-HomeSprite.png
Image: chatot.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Confide|Confide]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Taunt|Taunt]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growl|Growl]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mirror Move|Mirror Move]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Chatter|Chatter]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Voice|Hyper Voice]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sing|Sing]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Round|Round]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mimic|Mimic]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Echoed Voice|Echoed Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Roost|Roost]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Uproar|Uproar]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Feather Dance|Feather Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Boomburst|Boomburst]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
Number: 441
ShuffleToken: SRD-chatot-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 1.9
  Pounds: 4.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-chatot-BookSprite.png|wsmall]]
> ![[SRD-chatot-HomeSprite.png]]
> ![[SRD-chatot-BoxSprite.png|htiny]]
> ![[SRD-chatot-ShuffleToken.png|wsmall]]


*Music Note Pokemon*
*It mimics the cries of other Pokemon to trick them into thinking it’s one of them, this way they won’t attack it. Chatots that live with humans learn words and phrases but it’s unknown it they really know their meaning.*

**DexID**:: 0441
**Name**:: Chatot
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Tangled Feet|Tangled Feet]] ([[SRD-Big Pecks|Big Pecks]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 4.2lbs / 1.9kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Chatot.md"
flatten moves as T
where file.path = this.file.path
```
