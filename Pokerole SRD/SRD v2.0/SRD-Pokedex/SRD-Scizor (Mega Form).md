---
Ability1: Technician
Ability2: ''
BookSprite: SRD-scizor-mega-form-BookSprite.png
BoxSprite: SRD-scizor-mega-form-BoxSprite.png
DexCategory: Pincer Pokemon
DexDescription: The power of the Mega Stone puts its body trough tremendous stress,
  if it is inexperienced at wielding it and the battle is too long its pincers will
  feel heavy and even melt. They must be fast to rip their foes apart.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Scizorite
  Kind: Mega
  Pokemon: '[[SRD-Scizor]]'
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: ''
HomeSprite: SRD-scizor-mega-form-HomeSprite.png
Image: scizor-mega-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Feint|Feint]]'
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-False Swipe|False Swipe]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Bullet Punch|Bullet Punch]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Steel Wing|Steel Wing]]'
- - Pro
  - '[[SRD-Knock Off|Knock Off]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 212
ShuffleToken: SRD-scizor-mega-form-ShuffleToken.png
Type1: Bug
Type2: Steel
Weight:
  Kilograms: 125.0
  Pounds: 275.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-scizor-mega-form-BookSprite.png|wsmall]]
> ![[SRD-scizor-mega-form-HomeSprite.png]]
> ![[SRD-scizor-mega-form-BoxSprite.png|htiny]]
> ![[SRD-scizor-mega-form-ShuffleToken.png|wsmall]]


*Pincer Pokemon*
*The power of the Mega Stone puts its body trough tremendous stress, if it is inexperienced at wielding it and the battle is too long its pincers will feel heavy and even melt. They must be fast to rip their foes apart.*

**DexID**:: 0212M1
**Name**:: Scizor (Mega Form)
**Type**:: Bug / Steel
**Abilities**:: [[SRD-Technician|Technician]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 6'6" / 2.0m
**Weight**: 275.6lbs / 125.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon        | Kind   | Item      |
|:----------|:---------------|:-------|:----------|
| From      | [[SRD-Scizor]] | Mega   | Scizorite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Scizor (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
