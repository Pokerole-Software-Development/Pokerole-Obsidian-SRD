---
Ability1: Defiant
Ability2: Inner Focus
BookSprite: SRD-bisharp-BookSprite.png
BoxSprite: SRD-bisharp-BoxSprite.png
DexCategory: Sword Blade Pokemon
DexDescription: It leads a group of Pawniard. It battles to become the boss, but will
  be driven from the group if it loses. They are ruthless leaders and merciless with
  their foes. Weakness has no place among them.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Pawniard]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Pressure
HomeSprite: SRD-bisharp-HomeSprite.png
Image: bisharp.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - Ace
  - '[[SRD-Metal Burst|Metal Burst]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Pro
  - '[[SRD-Low Kick|Low Kick]]'
Number: 625
ShuffleToken: SRD-bisharp-ShuffleToken.png
Type1: Dark
Type2: Steel
Weight:
  Kilograms: 70.0
  Pounds: 154.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bisharp-BookSprite.png|wsmall]]
> ![[SRD-bisharp-HomeSprite.png]]
> ![[SRD-bisharp-BoxSprite.png|htiny]]
> ![[SRD-bisharp-ShuffleToken.png|wsmall]]


*Sword Blade Pokemon*
*It leads a group of Pawniard. It battles to become the boss, but will be driven from the group if it loses. They are ruthless leaders and merciless with their foes. Weakness has no place among them.*

**DexID**:: 0625
**Name**:: Bisharp
**Type**:: Dark / Steel
**Abilities**:: [[SRD-Defiant|Defiant]] / [[SRD-Inner Focus|Inner Focus]] ([[SRD-Pressure|Pressure]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 154.3lbs / 70.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Pawniard]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Bisharp.md"
flatten moves as T
where file.path = this.file.path
```
