---
Ability1: Rough Skin
Ability2: Sheer Force
BookSprite: SRD-druddigon-BookSprite.png
BoxSprite: SRD-druddigon-BoxSprite.png
DexCategory: Cave Pokemon
DexDescription: It runs through the narrow tunnels dug by Excadrill and Onix and uses
  its sharp claws to catch prey. It is cold blooded, and regularly takes sun baths
  to keep its energy. They are aggressive and territorial.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Mold Breaker
HomeSprite: SRD-druddigon-HomeSprite.png
Image: druddigon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Ace
  - '[[SRD-Rock Climb|Rock Climb]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Pro
  - '[[SRD-Poison Tail|Poison Tail]]'
Number: 621
ShuffleToken: SRD-druddigon-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 139.0
  Pounds: 306.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-druddigon-BookSprite.png|wsmall]]
> ![[SRD-druddigon-HomeSprite.png]]
> ![[SRD-druddigon-BoxSprite.png|htiny]]
> ![[SRD-druddigon-ShuffleToken.png|wsmall]]


*Cave Pokemon*
*It runs through the narrow tunnels dug by Excadrill and Onix and uses its sharp claws to catch prey. It is cold blooded, and regularly takes sun baths to keep its energy. They are aggressive and territorial.*

**DexID**:: 0621
**Name**:: Druddigon
**Type**:: Dragon
**Abilities**:: [[SRD-Rough Skin|Rough Skin]] / [[SRD-Sheer Force|Sheer Force]] ([[SRD-Mold Breaker|Mold Breaker]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 306.4lbs / 139.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Druddigon.md"
flatten moves as T
where file.path = this.file.path
```
