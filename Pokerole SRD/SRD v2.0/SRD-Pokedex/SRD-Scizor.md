---
Ability1: Swarm
Ability2: Technician
BookSprite: SRD-scizor-BookSprite.png
BoxSprite: SRD-scizor-BoxSprite.png
DexCategory: Pincer Pokemon
DexDescription: Its pincers appear to be two more heads and its wings are not for
  flying, but to regulate its body temperature. Scizor's body can shrug off most attacks
  and its pincers can crush almost any object.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Metal Coat
  Kind: Trade
  Pokemon: '[[SRD-Scyther]]'
- Evolves: To
  Item: Scizorite
  Kind: Mega
  Pokemon: '[[SRD-Scizor (Mega Form)]]'
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Light Metal
HomeSprite: SRD-scizor-HomeSprite.png
Image: scizor.png
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
ShuffleToken: SRD-scizor-ShuffleToken.png
Type1: Bug
Type2: Steel
Weight:
  Kilograms: 118.0
  Pounds: 260.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-scizor-BookSprite.png|wsmall]]
> ![[SRD-scizor-HomeSprite.png]]
> ![[SRD-scizor-BoxSprite.png|htiny]]
> ![[SRD-scizor-ShuffleToken.png|wsmall]]


*Pincer Pokemon*
*Its pincers appear to be two more heads and its wings are not for flying, but to regulate its body temperature. Scizor's body can shrug off most attacks and its pincers can crush almost any object.*

**DexID**:: 0212
**Name**:: Scizor
**Type**:: Bug / Steel
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Technician|Technician]] ([[SRD-Light Metal|Light Metal]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'9" / 1.8m
**Weight**: 260.1lbs / 118.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                    | Kind   | Item       |
|:----------|:---------------------------|:-------|:-----------|
| From      | [[SRD-Scyther]]            | Trade  | Metal Coat |
| To        | [[SRD-Scizor (Mega Form)]] | Mega   | Scizorite  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Scizor.md"
flatten moves as T
where file.path = this.file.path
```
